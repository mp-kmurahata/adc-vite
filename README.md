# adc-vite
For metaps Advent Calendar 2022

This project is a sample local development environment
that HMRs Typescript and Sass using Vite4 and Docker.

## How to use

after cloned

```bash
cd adc-vite
docker-compose build --no-cache
docker-compose up -d
docker-compose exec adc-vite-node /bin/bash
yarn
yarn dev
# let's access to http://localhost:3000
```

