---
title: GetEntity()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует URI в объект, содержащий реальный ресурс.
type: docs
weight: 14
url: /ru/aspose.slides.import/htmlexternalresolver/getentity/
---
## HtmlExternalResolver::GetEntity(System::String) метод

Преобразует URI в объект, содержащий реальный ресурс.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::HtmlExternalResolver::GetEntity(System::String absoluteUri) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Абсолютный URI объекта. |

### Возвращаемое значение

Объект [System::IO::Stream](../../../system.io/stream/) или null, если ресурс нельзя передать потоком.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [HtmlExternalResolver](../)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)