To run use:


```
docker run spidfire/android-docker:base -v `pwd`/gradle-cache:/root/.gradle ./gradlew assemble release fast
```