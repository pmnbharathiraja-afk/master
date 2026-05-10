# Simple Java Web Application for Jenkins CI/CD Demo

## Build Locally
```bash
mvn clean package
```

## Output
`target/simple-java-webapp.war`

## Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <YOUR_REPO_URL>
git push -u origin main
```

## Jenkins
Use either:
- Pipeline job (recommended) using the included `Jenkinsfile`
- Freestyle job with build step: `mvn clean package`
