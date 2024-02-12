<div align="center">

# asdf-scopes [![Build](https://github.com/salotz/asdf-scopes/actions/workflows/build.yml/badge.svg)](https://github.com/salotz/asdf-scopes/actions/workflows/build.yml) [![Lint](https://github.com/salotz/asdf-scopes/actions/workflows/lint.yml/badge.svg)](https://github.com/salotz/asdf-scopes/actions/workflows/lint.yml)

[scopes](https://scopes.readthedocs.io/en/latest/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add scopes
# or
asdf plugin add scopes https://github.com/salotz/asdf-scopes.git
```

scopes:

```shell
# Show all installable versions
asdf list-all scopes

# Install specific version
asdf install scopes latest

# Set a version globally (on your ~/.tool-versions file)
asdf global scopes latest

# Now scopes commands are available
scopes --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/salotz/asdf-scopes/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Sam Lotz](https://github.com/salotz/)
