# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

* added CONTRIBUTORS.md
* added pull request template
* added auto sync project struture
* added [autoflake8](https://pypi.org/project/autoflake/)
* added [flake8-bugbear](https://pypi.org/project/flake8-bugbear/)
* added [flake8-builtins](https://pypi.org/project/flake8-builtins/)
* added [flake8-comprehensions](https://pypi.org/project/flake8-comprehensions/)
* added [flake8-debugger](https://pypi.org/project/flake8-debugger/)
* added [pep8-naming](https://pypi.org/project/pep8-naming/)
* added support for python 3.9
* added [pdbpp](https://github.com/pdbpp/pdbpp) and [better-exceptions](https://github.com/qix-/better-exceptions)

### Changed

* automatically add new dependencies on template update

### Fixed

* remove double contributors file
* fixed file permissions, thanks @merwok

## [1.0.0] - 2020-10-06

### Added

* add github actions (test and release to pypi)

### Changed

* set supported python version to 3.6, 3.7 and 3.8
* set line_length to 88 (default of black)
* removed travis
* updated gitignore using [gitignore.io](https://gitignore.io)
* changelog is based on is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
* updated shields
* updated to poetry 1.1
* change default language of django to English

### Fixed

* add missing `.pre-commit-config.yaml`

## [0.1.0] - 2019-08-05

### Added

* travis CI
* flake8, isort, mypy and black
* Tests using pytest
* Run test using tox against multiple python versions
* preconfigured coveralls
* Django support
* User poetry to manage dependencies and publish releases

[Unreleased]: https://github.com/escaped/cookiecutter-pypackage/compare/1.0.0...HEAD
[1.0.0]: https://github.com/escaped/cookiecutter-pypackage/compare/0.1.0...1.0.0
[0.1.0]: https://github.com/escaped/cookiecutter-pypackage/tags/0.1.0
