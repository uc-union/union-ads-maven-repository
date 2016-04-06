# union-ads-maven-repository

## Usage

Add following repository info into gradle `repositories` entry

```gradle
repositories {
  maven {
    url 'https://raw.githubusercontent.com/uc-union/union-ads-maven-repository/master'
  }
}
```

Add dependencies

```gradle
dependencies {
  compile 'com.ucweb.union.ads:unionads:2.2.+'
}
```
