# asdf-ocaml

[OCaml](https://www.ocaml.org) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager


## Install

```shell
asdf plugin-add ocaml https://github.com/vic/asdf-ocaml.git
```

## Use

This plugin uses [OPAM](https://opam.ocaml.org/doc/Install.html) to install OCaml on your system.
You don't need to have a previous opam/ocaml installation for it to work.

After installation, `ocaml`, `opam`, and related tools will be available on your path.

```shell
# If you need to install a package that produces binaries
opam install foo

# Be sure to execute reshim afterwards to get them in your path
asdf reshim ocaml
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of OCaml.

