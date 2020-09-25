# testproject-java-maven

## Useful Commands

Install Dependencies:
```
mvn install
```

Basic Snyk Test (only tests root module):
```
snyk test
```

Multi-Module Snyk Test
```
snyk test --all-projects
```

Multi-Module Snyk Test (JSON Output)
This will output a single JSON document with a top-level array where each element is a full Snyk output object.
```
snyk test --all-projects --json
```
