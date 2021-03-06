# codacy-maven-plugin

Create and upload coverage report to https://codacy.com

## Usage

`mvn com.gavinmogan:codacy-maven-plugin:coverage -DcoverageReportFile=target/site/jacoco/jacoco.xml -DprojectToken=blah -DapiToken=blah`

where: 

* *coverageReportFile* is either a Jacoco or Cobertura file
* *projectToken* is your project token
* *apiToken* is your api token
*

**Enterprise**

To send coverage in the enterprise version you should:
```
export CODACY_API_BASE_URL=<Codacy_instance_URL>:16006
```

## License

MIT

## Contributing

I'm open to any and all forms of contribution. Documentation improvements, issues, pull requests, patches, test cases, etc.
