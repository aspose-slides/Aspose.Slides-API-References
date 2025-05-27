---
title: ExternalResourceResolver
second_title: Aspose.Sildes для .NET API Reference
description: Колбек-класс, используемый для разрешения внешних ресурсов при импорте документов Html Svg. Использование этого резольвера может создать уязвимость, когда предоставленный клиентом HTML или SVG файл заставит серверное программное обеспечение получить локальный или сетевой файл. Используйте с осторожностью. Рекомендуется вообще не указывать ExternalResourceResolver будут читаться только встроенные объекты или создать подкласс, который проверяет, действителен ли указанный uri.
type: docs
weight: 7250
url: /ru/aspose.slides.import/externalresourceresolver/
---

## Класс ExternalResourceResolver

Колбек-класс, используемый для разрешения внешних ресурсов при импорте документов Html, Svg. Использование этого резольвера может создать уязвимость, когда предоставленный клиентом HTML или SVG файл заставит серверное программное обеспечение получить локальный или сетевой файл. Используйте с осторожностью. Рекомендуется вообще не указывать ExternalResourceResolver (будут читаться только встроенные объекты) или создать подкласс, который проверяет, действителен ли указанный uri.

```csharp
public class ExternalResourceResolver : IExternalResourceResolver
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [ExternalResourceResolver](externalresourceresolver)() | Конструктор по умолчанию. |

## Методы

| Название | Описание |
| --- | --- |
| virtual [GetEntity](../../aspose.slides.import/externalresourceresolver/getentity)(string) | Отображает URI на объект, содержащий фактический ресурс. |
| virtual [ResolveUri](../../aspose.slides.import/externalresourceresolver/resolveuri)(string, string) | Разрешает абсолютный URI из базового и относительных URI. |

### Смотри также

* интерфейс [IExternalResourceResolver](../iexternalresourceresolver)
* пространство имен [Aspose.Slides.Import](../../aspose.slides.import)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->