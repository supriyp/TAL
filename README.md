# TAL

This repo contains tests for TALs website

## Getting Started

Please ensure you have the prerequisites installed for the tests to run

### Prerequisites

- The tests can be run only on a Mac OSX operating system
- You will need the chrome browser installed at the default path i.e. /Applications/Google Chrome.app/Contents/MacOS/Google Chrome
- You will need the at least version java JDK installed "1.8.0_131" or above
- You will need to have apache maven added to your PATH
- export PATH=/path to apache/apache-maven-3.5.0/bin:$PATH
- The Chrome Driver is included in the code, so you won't need to download that separately

## Running the tests

In order to run the tests, you need to go to the root directory under CafeTownSend and execute the below command

* mvn clean
* mvn test

### Future state

The tests need to be categorized into Smoke, Regression and Validation.

## Built Using

* [Cucumber-JVM](https://cucumber.io/docs/reference/jvm) - The framework used
* [Fluentlenium] (http://fluentlenium.org/) - Provides a fluent interface to Selenium
* [Maven](https://maven.apache.org/) - Dependency Management

## Authors

* **Supriya Pawar** - *Initial work* - [Supriya's Projects](https://github.com/SupriyaProjects)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Google and Stackoverflow