## Minor Fix
This is a submission for a minor fix. In this version I have:

* inserted `suppressWarnings(RNGversion("3.5.0"))` before calling set.seed() in my example, vignette and test code, because of the check problems with current R-devel 


## Test environments
* local macOS install, R 3.5.1
* ubuntu 16.04 (on travis-ci), R 3.5.1
* win-builder (devel and release)

## R CMD check results

0 errors | 0 warnings | 0 note

* This is a release with minor fixes.
