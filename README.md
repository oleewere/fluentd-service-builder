# fluent-service-builder

FluentD service package builder. Currently support only RPM packages

## Description

- configurable package name / version
- configurable fluentd plugins (profile based)

## Requirements

- docker
- python3.5+
- pip3

## Usage

```bash
make install-rpm
```

## Release

```
git tag "1.0.0"
make release
```

## Development

```
python3 -m venv env1
python3 setup.py install
python3 packager/cli.py --help
```

## TODOs
- support Windows/MacOS/deb packages
