# flyway demo

This project is used to test out flyway usability at different environments.

Tested environments:

- MacOS
- Ubuntu 16.04

## Command

- Set up baseline

```bash
flyway baseline
```

- Get migration info

```bash
flyway info
```

- Migrate database 

```bash
flyway migrate
```

- Clean Database

```bash
flyway clean
```

## Installation

- Mac

```bash
brew install flyway
```

- Ubuntu 16.04

    1. Download from flyway official website

    2. Add flyway to path

    ```bash
    cd /usr/local/bin
    ln -s /path/to/flyway flyway
    ```
