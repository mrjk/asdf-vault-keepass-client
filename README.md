<div align="center">

# asdf-vault-keepass-client [![Build](https://github.com/mrjk/asdf-vault-keepass-client/actions/workflows/build.yml/badge.svg)](https://github.com/mrjk/asdf-vault-keepass-client/actions/workflows/build.yml) [![Lint](https://github.com/mrjk/asdf-vault-keepass-client/actions/workflows/lint.yml/badge.svg)](https://github.com/mrjk/asdf-vault-keepass-client/actions/workflows/lint.yml)

[vault-keepass-client](https://github.com/mrjk/vault-keepass-client) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add vault-keepass-client
# or
asdf plugin add vault-keepass-client https://github.com/mrjk/asdf-vault-keepass-client.git
```

vault-keepass-client:

```shell
# Show all installable versions
asdf list-all vault-keepass-client

# Install specific version
asdf install vault-keepass-client latest

# Set a version globally (on your ~/.tool-versions file)
asdf global vault-keepass-client latest

# Now vault-keepass-client commands are available
vault-keepass-client
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrjk/asdf-vault-keepass-client/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mrjk](https://github.com/mrjk/)
