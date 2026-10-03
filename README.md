# Device Faker

A configurable Zygisk-based Android device spoofing project with a native Rust CLI and configuration tooling.

## Project Structure

- `device_faker_cli/` — Rust command-line tooling
- `config` — device configuration submodule
- `docs/` — configuration and changelog documentation
- `.github/workflows/` — automated builds

## Requirements

- Compatible Android build environment
- Test/rooted Android environment with the required Zygisk support
- Rust toolchain for the CLI
- Git submodules

## Setup

```bash
git clone --recurse-submodules https://github.com/ryoaonetsuki/device-faker.git
cd device-faker
```

If the repository was cloned without submodules:

```bash
git submodule update --init --recursive
```

## Configuration

Read [docs/README.md](docs/README.md) before configuring or installing the module. Use the project documentation for the supported device-profile options.

## Build

Use the repository's included build configuration and GitHub Actions workflow for the supported build process. Build the Rust CLI with the project's Rust configuration when required.

## Documentation

See [docs/README.md](docs/README.md) for detailed configuration and changelog information.

## License

See [LICENSE](LICENSE).

## Safety

Use device spoofing only on devices and software you own or are authorized to test.
