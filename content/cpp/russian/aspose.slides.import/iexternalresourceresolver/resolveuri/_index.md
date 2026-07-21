---
title: ResolveUri()
second_title: Aspose.Slides для C++ справочник API
description: Разрешает абсолютный URI из базового и относительного URI.
type: docs
weight: 1
url: /ru/aspose.slides.import/iexternalresourceresolver/resolveuri/
---
## IExternalResourceResolver::ResolveUri(System::String, System::String) метод

Разрешает абсолютный URI из базового и относительного URI.

```cpp
virtual System::String Aspose::Slides::Import::IExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | Базовый URI связывающих объектов |
| relativeUri | [System::String](../../../system/string/) | Относительный URI к связанному объекту. |

### Возвращаемое значение

Абсолютный URI или null, если относительный URI не может быть разрешён.

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [IExternalResourceResolver](../)
* Пространство имён [Aspose::Slides::Import](../../)
* Библиотека [Aspose.Slides](../../../)