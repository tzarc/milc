# Breaking Changes

This is a list of breaking changes that have been made to MILC. If your script stops working after a minor or major version upgrade this document will tell you how to fix it.

# Version 1.3.0

* New global arguments: --unicode and --no-unicode
* ANSIFormatter, ANSIStrippingFormatter, ANSIEmojiLoglevelFormatter, and ANSIStrippingEmojiLoglevelFormatter have been removed in favor of `format_ansi()` being color aware. The new `MILCFormatter` is being used in its place.

# Version 1.2.0

* The config file is now resolved to the actual file which should avoid overwriting symlinks. <https://github.com/qmk/qmk_cli/issues/43>

# Version 1.1.0

* Configuration: 0 and 1 are now considered integers, not boolean

# Version 1.0.0

Initial Version