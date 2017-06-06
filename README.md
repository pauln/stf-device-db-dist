# stf-device-db-dist

**stf-device-db-dist** is an alternative source for [stf-device-db](https://github.com/openstf/stf-device-db), as the NPM package hasn't been updated for quite some time.

## Usage

To use this alternative source, modify `package.json` in your `stf` installation to list the `stf-device-db` dependency as follows:
`"stf-device-db": "pauln/stf-device-db-dist",`

Then run `npm update stf-device-db` (within your `stf` installation) in order to replace your existing `stf-device-db` with this one.