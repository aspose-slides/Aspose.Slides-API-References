---
title: GetUrl()
second_title: Aspose.Slides для C++ справочник API
description: "Возвращает URL внешнего объекта. Этот метод всегда вызывается, если ILinkEmbedController::GetObjectStoringLocation вернул LinkEmbedDecision::Link и может быть вызван, если ILinkEmbedController::GetObjectStoringLocation вернул LinkEmbedDecision::Embed, но внедрение невозможно. Может быть вызван многократно для того же идентификатора объекта."
type: docs
weight: 14
url: /ru/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) метод

Возвращает URL внешнего объекта. Этот метод всегда вызывается, если [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) вернул [LinkEmbedDecision::Link](../../linkembeddecision/), и может быть вызван, если [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) вернул [LinkEmbedDecision::Embed](../../linkembeddecision/), но внедрение невозможно. Может быть вызван многократно для того же идентификатора объекта.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | **int32_t** | Идентификатор объекта. Этот идентификатор уникален во всей операции. |
| referrer | **int32_t** | Идентификатор ссылающегося объекта или 0, если объект ссылается на корневой документ. Может использоваться для генерации относительной ссылки. |

### Возвращаемое значение

URL внешнего объекта или null, если этот объект следует игнорировать.

## См. также

* Класс [String](../../../system/string/)
* Класс [ILinkEmbedController](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)