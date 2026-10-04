# dotfiles

My personal configuration files and system setup for macOS and other devices.

This repository serves as a central place for the configurations, scripts, and settings I use across my devices. It is primarily intended for my own use, but feel free to explore, reuse, and adapt anything that might be useful for your own setup.

## Structure

```text
dotfiles/
├── macos/      # macOS configuration and application settings
├── beepy/      # Beepy configuration
├── LICENSE
└── README.md
```

The repository will evolve over time as additional applications, shell configurations, and system settings are added.

Not all configurations are necessarily portable between machines. Review them before applying them to your own system.

## Installation

Clone the repository:

```bash
git clone https://github.com/pjanze/dotfiles.git ~/dotfiles
cd ~/dotfiles
```

Configuration files can then either be copied to their respective locations or linked using symbolic links.

Example:

```bash
ln -s ~/dotfiles/macos/ghostty ~/.config/ghostty/config
```

## Security

This is a public repository.

No passwords, API keys, private SSH keys, access tokens, certificates, or other secrets are stored here.

## Disclaimer

These configurations reflect parts of my personal setup and preferences. They may change at any time and are provided without any guarantee that they will work on other systems.

If you use parts of this repository, review the configuration before applying it to your own environment.

## License

This repository is licensed under the [MIT License](LICENSE).

You are free to use, modify, and distribute the contents in accordance with the terms of the license.
