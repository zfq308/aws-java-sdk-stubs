# aws-java-sdk-stubs
[![Build Status](https://drone.io/github.com/bizo/aws-java-sdk-stubs/status.png)](https://drone.io/github.com/bizo/aws-java-sdk-stubs/latest)
## Services should come with stubs

This project provides stub classes for the [aws-sdk-java](https://github.com/aws/aws-sdk-java) services to make writing good tests much easier.

[See Services should come with stubs](http://www.draconianoverlord.com/2013/04/13/services-should-come-with-stubs.html) and [Why I don't like mocks](http://www.draconianoverlord.com/2010/07/09/why-i-dont-like-mocks.html) on [Stephen's blog](http://www.draconianoverlord.com/).

## Download

See [Releases](https://github.com/bizo/aws-java-sdk-stubs/releases/) for release notes and downloadable jars.

## Building/Eclipse

`mvn eclipse:eclipse` to generate eclipse configuration (although these are also checked in)

`mvn clean test` to compile and run tests

`mvn clean package` to build the jar

Make sure M2_REPO is defined in java build path classpath variables

## License
[Apache 2](http://www.apache.org/licenses/LICENSE-2.0.html)