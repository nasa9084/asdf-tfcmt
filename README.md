<div align="center">

# asdf-tfcmt [![Build](https://github.com/nasa9084/asdf-tfcmt/actions/workflows/build.yml/badge.svg)](https://github.com/nasa9084/asdf-tfcmt/actions/workflows/build.yml) [![Lint](https://github.com/nasa9084/asdf-tfcmt/actions/workflows/lint.yml/badge.svg)](https://github.com/nasa9084/asdf-tfcmt/actions/workflows/lint.yml)

[tfcmt](https://suzuki-shunsuke.github.io/tfcmt/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add tfcmt
# or
asdf plugin add tfcmt https://github.com/nasa9084/asdf-tfcmt.git
```

tfcmt:

```shell
# Show all installable versions
asdf list-all tfcmt

# Install specific version
asdf install tfcmt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tfcmt latest

# Now tfcmt commands are available
tfcmt --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nasa9084/asdf-tfcmt/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [nasa9084](https://github.com/nasa9084/)
