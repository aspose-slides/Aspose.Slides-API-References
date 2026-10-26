---
title: GetObjectStoringLocation()
second_title: Aspose.Slides для C++ API Reference
description: Определяет, где должен храниться объект. Этот метод вызывается один раз для каждого идентификатора объекта. Не гарантируется, что не будет двух объектов с одинаковыми данными, semanticName и contentType, но с разными идентификаторами.
type: docs
weight: 1
url: /ru/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) method


Определяет, где должен храниться объект. Этот метод вызывается один раз для каждого идентификатора объекта. Не гарантируется, что не будет двух объектов с одинаковыми данными, semanticName и contentType, но с разными идентификаторами.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| id | **int32_t** | Идентификатор объекта. Этот идентификатор уникален в рамках операции сохранения. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Бинарные данные объекта. Этот параметр может быть null, если бинарные данные объекта еще не сгенерированы. |
| semanticName | [System::String](../../../system/string/) | Краткий текст, описывающий смысл объекта. Контроллер может использовать его как часть внешнего имени объекта, но обеспечение уникальности имен и их соответствия разрешённым символам лежит на диспетчере. |
| contentType | [System::String](../../../system/string/) | MIME-тип объекта. |
| recomendedExtension | [System::String](../../../system/string/) | Расширение имени файла, рекомендованное для этого MIME-типа. |

### Return Value

Decision

## See Also

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ILinkEmbedController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)