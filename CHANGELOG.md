## [Unreleased]

## 1.0.7 -

Fix regression that snuck in with a 1.0.6 commit

## 1.0.6 -

Support comma separated prop values on multiple lines fixes
Allow px for multiple values in shorthand lean string
Allow conditionals for `$media` and `$nest`

## 1.0.5 -

Revert usage of getComputedStyle for prop resolution

## 1.0.4 -

Fixed property resolution bug in firefox

## 1.0.3 - 

Added `letter-spacing` as preferred `ls` shortname
Fixed unsetting props when using setter functions
Use getComputedStyle for property registration (fixes safari 5)

## 1.0.2 - 

Convenience toString helper changed to valueOf
Fixed px being added to flex shorthand unexpectedly
Lazy registration of px value properties
Add multiple properties per line for css strings

## 1.0.1 - 

Fixed px property registration in edge
Fixed px addition for shorthands

## 1.0.0 - 2017-09-05

First stable release of `bss`. Changes from here on will follow [semver](http://semver.org/).
- Made 

[Unreleased]: https://github.com/porsager/bss/compare/v1.0.0...HEAD
