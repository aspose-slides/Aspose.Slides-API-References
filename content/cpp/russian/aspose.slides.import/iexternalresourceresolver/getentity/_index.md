---
title: GetEntity()
second_title: Справочник API Aspose.Slides для C++
description: Сопоставляет URI с объектом, содержащим фактический ресурс.
type: docs
weight: 14
url: /ru/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) method


Сопоставляет URI с объектом, содержащим фактический ресурс.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Абсолютный URI объекта. |

### Return Value

Объект [System::IO::Stream](../../../system.io/stream/) или null, если ресурс нельзя потоково передать.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)