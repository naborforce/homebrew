<p align="center">
  <a href="https://github.com/naborforce/homebrew" target="_blank">
    <img src="https://private-user-images.githubusercontent.com/6691906/275630407-c078b007-5414-4684-83fa-fbff2f065255.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDk4MzU3MzAsIm5iZiI6MTcwOTgzNTQzMCwicGF0aCI6Ii82NjkxOTA2LzI3NTYzMDQwNy1jMDc4YjAwNy01NDE0LTQ2ODQtODNmYS1mYmZmMmYwNjUyNTUucG5nP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI0MDMwNyUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNDAzMDdUMTgxNzEwWiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9ZWU3MDFkZTI3MmI0OWYzNmQxNmE4MjNkMWQ2YzQ4YzkzZjY1OTk4ZDlkNjFhNTUwYjA4NWFmZWZhMGQyY2I2NyZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QmYWN0b3JfaWQ9MCZrZXlfaWQ9MCZyZXBvX2lkPTAifQ.TfuFpvFmNWN7bBa4krGjOqUrR8i5sFKdifJQjwkokZQ" alt="Homebrew Tap for PHP" width="560">
  </a>
</p>

<h1 align="center">brew tap naborforce/homebrew</h1>

## Legacy NodeJs Support

| Node Version  | NTS Formula        |
|---------------|--------------------|
| Node 14       | `node@14`          |


## Usage

### Prerequisites

- On macOS, install Xcode Command Line Utilities:

```zsh
xcode-select --install
```

- On Linux, install cURL and Git:

```bash
# Using APT
sudo apt-get install -y curl git

# Using Yum
sudo yum install -y curl git
```

- Install Homebrew:

```zsh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

- If previously installed, update homebrew and the formulae:

```zsh
brew update
```

- If you have packages from old `homebrew/php` tap, refer to [this guide](https://github.com/naborforce/homebrew/wiki/Cleanup) for removing them.

### Add this tap

Fetch the formulae in this tap:

```zsh
brew tap naborforce/homebrew
```

### Install Node

- For example, to install `Node 14`:

```zsh 
brew install naborforce/homebrew/node@14
```

- After installing you have to link it:

```zsh
brew link --overwrite --force naborforce/homebrew/node@14
```

- Restart the terminal and test your NodeJs version:

```zsh
node -v
```

## License

The code in this project is licensed under the [MIT license](http://choosealicense.com/licenses/mit/).
Please see the [license file](LICENSE) for more information.

This project has some [dependencies](#dependencies), and their license can be found [here](LICENSE_HOMEBREW).


## Contributions

Contributions are welcome!
Please see [Contributor's Guide](.github/CONTRIBUTING.md "naborforce/homebrew contribution guide") before you start.
If you face any issues while using this tap or want to suggest a feature/improvement, create an discussion thread 
[here](https://github.com/naborforce/homebrew/discussions "naborforce/php discussions").


## Dependencies

- [Homebrew/brew](https://github.com/Homebrew/brew "Homebrew GitHub Repo")
- [Homebrew/homebrew-core](https://github.com/Homebrew/homebrew-core "Homebrew core tap")
- [Homebrew/actions](https://github.com/Homebrew/actions "Homebrew GitHub Actions")
