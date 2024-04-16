<div align="center">

# asdf-xcodehero [![Build](https://github.com/tuist/asdf-xcodehero/actions/workflows/build.yml/badge.svg)](https://github.com/tuist/asdf-xcodehero/actions/workflows/build.yml) [![Lint](https://github.com/tuist/asdf-xcodehero/actions/workflows/lint.yml/badge.svg)](https://github.com/tuist/asdf-xcodehero/actions/workflows/lint.yml)

Plugin to install [xcodehero](https://github.com/tuist/xcodehero)

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
asdf plugin add xcodehero https://github.com/tuist/asdf-xcodehero.git
mise plugin add xcodehero https://github.com/tuist/asdf-xcodehero.git
```

xcodehero:

```shell
# Show all installable versions
asdf list-all xcodehero

# Install specific version
asdf install xcodehero latest

# Set a version globally (on your ~/.tool-versions file)
asdf global xcodehero latest

# Now xcodehero commands are available
xcodehero --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tuist/asdf-xcodehero/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tuist](https://github.com/tuist/)
