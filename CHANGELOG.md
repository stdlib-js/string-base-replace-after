# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2025-08-25)

<section class="commits">

### Commits

<details>

-   [`3d2f3c7`](https://github.com/stdlib-js/stdlib/commit/3d2f3c70a73bfb11428d490e91c04f4744d32d23) - **docs:** clean-up example code _(by Philipp Burckhardt)_
-   [`2825b42`](https://github.com/stdlib-js/stdlib/commit/2825b42e8cd7483d15dfed1c6b389bfcb86d7ca0) - **docs:** update related packages sections [(#3898)](https://github.com/stdlib-js/stdlib/pull/3898) _(by stdlib-bot)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.1.1">

## 0.1.1 (2024-07-26)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2024-04-13)

<section class="features">

### Features

-   [`b665537`](https://github.com/stdlib-js/stdlib/commit/b6655370f23b4bfdccc19c55af18699c2f368020) - resolve negative indices relative to the last string character
-   [`04ee89f`](https://github.com/stdlib-js/stdlib/commit/04ee89f626756ab9da99b864ccbb9897964a568d) - add `string/base/replace-after` [(#1363)](https://github.com/stdlib-js/stdlib/pull/1363)

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`b665537`](https://github.com/stdlib-js/stdlib/commit/b6655370f23b4bfdccc19c55af18699c2f368020): resolve negative indices relative to the last string character

    -   Previously, a negative index would resolve to `0`. This commit changes
        that behavior to resolve relative to the last index. To preserve
        previous behavior, users should clamp `fromIndex` values to string
        bounds before calling into `replaceAfter`.

</section>

<!-- /.breaking-changes -->

<section class="issues">

### Closed Issues

This release closes the following issue:

[#812](https://github.com/stdlib-js/stdlib/issues/812)

</section>

<!-- /.issues -->

<section class="commits">

### Commits

<details>

-   [`b5c7e64`](https://github.com/stdlib-js/stdlib/commit/b5c7e647156eaf0ca5234210b2f98b0c22bd7ed7) - **docs:** update examples _(by Athan Reines)_
-   [`b665537`](https://github.com/stdlib-js/stdlib/commit/b6655370f23b4bfdccc19c55af18699c2f368020) - **feat:** resolve negative indices relative to the last string character _(by Athan Reines)_
-   [`04ee89f`](https://github.com/stdlib-js/stdlib/commit/04ee89f626756ab9da99b864ccbb9897964a568d) - **feat:** add `string/base/replace-after` [(#1363)](https://github.com/stdlib-js/stdlib/pull/1363) _(by Golden Kumar, Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Golden Kumar

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

