I am using npm to manage my packages. I added a package in npm using an alias.

Then there was an update to the installed package. Renovate notified me of the update.

In the updated package-lock.json, the package has been added to dependencies as well as devDependencies.

see: https://github.com/naokiy/reproduce-renovate-npm-alias-dev-two/pull/4/files