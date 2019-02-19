### Why

Deploys the public pact-broker script into our Elastic Beanstalk environment.

### Deployment

Deployment is handled via travis CI and will automatically deploy on a push
of a tagged commit.

```
git tag <version>
git push origin master --tags
git push origin
```
