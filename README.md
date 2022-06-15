# tleerai.github.io


The index.html in the top directory serves as the main index which lists each package and the directory where you can find each version.

Inside the package directory will be another index.html with multiple links to each version of the package. The version of 
the egg: `#egg=retl-0.1` 0.1 in this case, must match the value inside the package's meta data. The Git tag which contains 
this version and the hyperlink text do not need to match the version, but should for obvious reasons.  

These version and package names metadata are publicly visible on the internet however they point toward private git repositories:
`git+https://github.com/tleerai/fakeretl.git@0.0.3#egg=retl-0.1`

These repositories are not accessible without github.com authentication.
