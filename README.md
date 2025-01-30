# Тесты для NuGet пакета KafkaFlow.3.0.10

## Информация о пакете

Ссылка на Nuget.org: https://www.nuget.org/packages/KafkaFlow/3.0.10
Ссылка на github.com: https://github.com/Farfetch/kafkaflow/releases/tag/3.0.10

## Информация о тестовом проекте

Папка `nugets` содержит требуемые NuGet пакеты, включая `KafkaFlow.3.0.10.nupkg`
Папка `KafkaFlow.UnitTests` содержит тестовый проект на xunit
Файл nuget.config определяет изолированную среду для восстановления NuGet пакетов.

Проект рассчитан на .NET 6

### Запуск тестов

```shell
dotnet test
```

Запускать в корневой папке