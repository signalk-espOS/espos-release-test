# espos-release-test

A test fixture, not a firmware anyone should flash. It is espOS's
`from_registry` example exactly as `idf.py create-project-from-example`
delivers it, plus a release workflow that calls espOS's reusable
`release-firmware.yml`. Its releases exercise the build, the GitHub release
assets, the browser-readable `release-assets` mirror and its retention, and the
backfill of older releases.

Signed with a throwaway key kept only as this repository's secret.
