## v0.12.3-tc.0 · 13 December 2019

#### Note: v0.12.3-tc.0 is v0.12.2 with two TC related changes, so it's essentially a v0.12.3 prerelease version with only TC changes in it.
*  Add drop-up feature.

   *@becquersant*

*  Fix firefox issue. 

   *@becquersant*

## v0.12.2 · 23 June 2016
*  Fix issue preventing build ("Cannot assign to read only property
   'subarray'") because of bug in uglifyjs. (#1072)

   *@jaridmargolin*

*  Fix tabbing issue (#877) on IE11. (#997)

   *@bwilson-ux*

*  Fix jQuery initialization for jQuery >= 1.9 (#1045)

   *@mpokrywka*

*  Make `remove_button` work for single-option usage (#848)

   *@ChoppyThing*

*  Fixed bug that made `allowEmptyOption: true` useless (#739)

   *@mcavalletto*

*  Functions in option `render` can now return a DOM node in addition to
   text. (#617)
