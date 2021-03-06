# Changelog

## [2.0.0]
### Updates
- Compatibility with residue server 2.0.0

## [1.0.3]
### Updates
- Added support for immediate close

## [1.0.2]
### Updates
- Added compression and bulk request support

## [1.0.1]
### Updates
- Internal log to file (`<session_dir>/internal.log`) instead of console

## [1.0.0]
### Updates
- Support `%thread`
- printf like support

### Fixes
- Fixed `%vlevel`

## [0.0.4]
### Updates
- Lock while connecting

## [0.0.3]
### Updates
- Support `requires_timestamp` flag
- UTC support
- Time offset support

### Fixes
- Fix `write_log` when `validate_connection` returns false

## [0.0.2]
### Improvements
 - Logging command is run in background

### Updates
 - Added `Logger` class for public use
 - Changed `Residue::instance` to `Residue::init`

## [0.0.1]
 - Initial release

