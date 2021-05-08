# back-java-parent

## Install
In order to have a functional workspace, link folders domain, infrastructure and application to a git subrepo. For instance to get the application with SpringBoot and without database :
```
git submodule add git@github.com:the-demo-app/back-java-domain.git domain
git submodule add git@github.com:the-demo-app/back-java-infrastructure-inmemory.git infrastructure
git submodule add git@github.com:the-demo-app/back-java-application-springboot-2.git application
```