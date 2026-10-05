<!-- tyhp-readme:start -->
# tyhpdef/fruitcake-laravel-debugbar

Tyhp type definitions for `fruitcake/laravel-debugbar` `4.4.3`.

```bash
composer require --dev tyhpdef/fruitcake-laravel-debugbar:4.4.3
```

This is a metapackage. Composer also installs `tyhpdef/fruitcake-laravel-debugbar-impl` (type files).
Require **this** name, not `tyhpdef/fruitcake-laravel-debugbar-impl`.

See https://tyhplang.com.

## Maintain `fruitcake/laravel-debugbar`? Ship the types yourself

If you are a Packagist maintainer of `fruitcake/laravel-debugbar`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/fruitcake-laravel-debugbar-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `fruitcake/laravel-debugbar` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/fruitcake-laravel-debugbar": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `fruitcake/laravel-debugbar` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `fruitcake/laravel-debugbar` with a real constraint,
   `"replace": { "tyhpdef/fruitcake-laravel-debugbar": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `fruitcake/laravel-debugbar` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/fruitcake-laravel-debugbar` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
