# Kontena CLI Tools

## Installing Kontena CLI

### MacOS (OSX)

You can install Kontena CLI using our [official installer](https://gh-releases.kontena.io/kontena/kontena/pkg/latest) or [Homebrew](https://brew.sh/) :

```
$ brew install kontena
```

To install the current unstable development version, you can use:

```
$ brew install --HEAD kontena
```

### Debian / Ubuntu

You can install Kontena CLI using our [official deb package](https://gh-releases.kontena.io/kontena/kontena/deb/latest).

### Linux / Windows

> Prerequisites: You'll need Ruby version 2.1 or later installed on your system. For more details, see the official [Ruby installation docs](https://www.ruby-lang.org/en/documentation/installation/).


You can install the Kontena CLI using the Rubygems package manager, which is included in Ruby.

```
$ gem install kontena-cli
```

After the installation is complete, you can test the installation by checking the Kontena CLI version with `kontena version`.

**OPTIONAL**

To enable tab-completion for bash, add the following to your `.bashrc` scripts:

```
which kontena > /dev/null && . "$( kontena whoami --bash-completion-path )"
```
