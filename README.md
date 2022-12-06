gradle-reproducer-22875
=======================

Reproducer for https://github.com/gradle/gradle/issues/22875. `cd main-project` and run `./gradlew licenseReport` to see it work with 7.5.1. Then do `./gradlew wrapper --gradle-version=7.6` and try again to see it fail.
