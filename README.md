## AWS Copilot CLI Sample App

notes to future me:
```
source login.sh

copilot env init
# it will walk you through importing resources

# then deploy
copilot init --app demo \
  --name api \
  --type "Load Balanced Web Service" \
  --dockerfile "./Dockerfile" \
  --deploy
```

Then update the manifests to use DNS, ACM
