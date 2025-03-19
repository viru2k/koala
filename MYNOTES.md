Configurar Module Federation


Para configurar las aplicaciones remotas (login y agenda):

npx nx generate @nrwl/angular:setup-mf --appName=login-app --mfType=remote
npx nx generate @nrwl/angular:setup-mf --appName=agenda-app --mfType=remote


docker-compose down -v
docker-compose up -d
docker-compose logs -f db

local docker example C:\repositories\monorepo\backoffice-monorepo

## Launch openapi generator 
## Autogenerate service and models for frontend
npx ng-openapi-gen
