# DEPENDENCY CONFUSION POC
#### The project shows that a non-existent dependency can be circumvented even if "scoped package" is used.
##### https://www.zdnet.com/article/microsoft-warns-enterprises-of-new-dependency-confusion-attack-technique/

### GET STARTED
- docker-compose up
- npm adduser --registry http://localhost:4873
- npm login --registry http://localhost:4873
- npm publish --registry http://localhost:4873 # By default, scoped packages are published with private visibility.
- cd confused
- npm i or npm ci