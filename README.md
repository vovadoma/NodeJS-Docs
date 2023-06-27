# NodeJS-Server
NodeJS Applications

#### Features
- Prisma schema -> JSON schema -> d.ts converter
- JSON Schema validation (record schema, listView, api, action, event)
- API transport (http/ws) and HTTP 2/3
- CRUD API (auto generation from the schema) (v1)
- JSON:API (crud, query builder to PostgresSQL, Serialize JSON:API) (v2)
- Action, Event: API (v3)
- Dictionary API (memory cache, RPC update, periodical, pre defined)
- Entity: record, recordTablePart, recordListView
- Entity: OLAP Cube, cubeBalance, cubeTurnover (schema property, movement table, period types, date, +/-, value, dimensions)
- Workers, job, scheduling (app side)
- Module structure (users (entity): service, repository, api)
- Bus for external API (like metacom bus)
- RBAC
- Oauth 2.0
- Versions
- Cache like as memory Map or redis

#### Applications:
- quiz (learn english words, use any open api for words and translate, telegram chanel)
- messenger (course task)
- openprocurement.api’s parser and client

#### Open API:
- https://public.api.openprocurement.org/api/2.3/tenders (bus.openprocurement.getTender(id))
- any currency rates
- OpenDataBot
- GPT-4 API
- Elastic or Postgres search

#### Dependencies:
- pg
- ws
- pino
