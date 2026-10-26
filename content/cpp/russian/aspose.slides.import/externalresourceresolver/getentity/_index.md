---
title: GetEntity()
second_title: Справочник API Aspose.Slides для C++
description: Отображает URI в объект, содержащий фактический ресурс.
type: docs
weight: 14
url: /ru/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) метод

Maps a URI to an object containing the actual resource.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Абсолютный URI к объекту. |

### Возвращаемое значение

Объект [System::IO::Stream](../../../system.io/stream/) или null, если ресурс невозможно передать потоково.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Stream](../../../system.io/stream/)
* Класс [String](../../../system/string/)
* Класс [ExternalResourceResolver](../)
* Пространство имён [Aspose::Slides::Import](../../)
* Библиотека [Aspose.Slides](../../../)