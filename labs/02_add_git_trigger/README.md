# Adding GitHub Triggers

This folder holds the files for the lab: _Adding GitHub Triggers_ which is part of the **IBM-CD0215EN-Skills Network Introduction to CI/CD** course.

## Json Event Request:

```json
{
  "ref": "main",
  "repository": {
    "url": "https://github.com/ibm-developer-skills-network/"
  }
}
```

## Curl Request:

```cmd
curl -X POST http://localhost:8090 \
  -H 'Content-Type: application/json' \
  -d '{"ref":"main","repository":{"url":"https://github.com/ibm-developer-skills-network/wtecc-CICD_PracticeCode"}}'
```
