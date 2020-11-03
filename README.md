[![](https://jitpack.io/v/sercangedik/dagger1-shaded.svg)](https://jitpack.io/#sercangedik/dagger1-shaded)


# Dagger 1 Shaded 🗡️

1. Add this to your build:

```groovy
repositories {
  maven { url "https://jitpack.io" }
}

dependencies {
  implementation 'com.github.sercangedik.dagger1-shaded:dagger1-shaded-library:1.0.0'
  annotationProcessor 'com.github.sercangedik.dagger1-shaded:dagger1-shaded-compiler:1.0.0'
}
```

This project referenced to https://github.com/blinkist/dagger2-shaded and I inspired from https://medium.com/@kaciula/thanks-for-answering-6ad3450e9c5b this comment. Thanks to [@tfcporciuncula](https://github.com/tfcporciuncula) and [@kaciula](https://github.com/kaciula)

## Updating and building

- Change the `dagger.version` property in the parent POM to the desired value. (Current version 1.2.2)
- Run `mvn package` to generate the JARs and use them directly in your project or you can use jar's inside of project
- ...or make the changes in a fork and use [JitPack](https://jitpack.io/). And open a PR if it's a new version!# dagger1-shade
