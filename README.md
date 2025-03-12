<div align="center">

# asdf-lazysql [![Build](https://github.com/plavelo/asdf-lazysql/actions/workflows/build.yml/badge.svg)](https://github.com/plavelo/asdf-lazysql/actions/workflows/build.yml) [![Lint](https://github.com/plavelo/asdf-lazysql/actions/workflows/lint.yml/badge.svg)](https://github.com/plavelo/asdf-lazysql/actions/workflows/lint.yml)

[lazysql](https://github.com/jorgerojas26/lazysql) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add lazysql
# or
asdf plugin add lazysql https://github.com/plavelo/asdf-lazysql.git
```

lazysql:

```shell
# Show all installable versions
asdf list-all lazysql

# Install specific version
asdf install lazysql latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lazysql latest

# Now lazysql commands are available
lazysql --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/plavelo/asdf-lazysql/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [plavelo](https://github.com/plavelo/)
