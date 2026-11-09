# Q Tools

## Tests

From the workspace root (the parent directory of `Plugin` and `Tools`), install the shared development dependencies and run both PHPUnit suites:

```sh
composer install
composer test
```

Keep PHP source files in `_src` and PHPUnit configuration and tests in `_test`. The shared Composer dependencies are installed in the workspace-level `vendor` directory.