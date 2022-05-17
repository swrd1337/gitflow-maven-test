# gitflow-maven-test

[Gitflow Maven Plugin URL](https://github.com/aleksandr-m/gitflow-maven-plugin)

Used commands:
* Create release branch -> `mvn gitflow:release-start -DuseSnapshotInRelease=true`
* Integrate release branch into main & delete release branch -> `mvn gitflow:release-finish -DuseSnapshotInRelease=true`
