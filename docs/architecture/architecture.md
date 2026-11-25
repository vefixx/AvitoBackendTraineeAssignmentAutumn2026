# Архитектура
## Clean Architecture
- **WebApi**: HTTP-уровень, контроллеры, middleware, команды и запросы к MediatR.
- **Application Layer**: сценарии использования приложения. Здесь находятся команды и запросы MediatR, их обработчики, DTO, валидаторы и интерфейсы.
- **Domain Layer**: сущности, Value Objects, перечисления и бизнес-правила.
- **Infrastructure Layer**: реализации интерфейсов Application: EF Core, DbContext, репозитории, интеграции с внешними сервисами и файловое хранилище.
