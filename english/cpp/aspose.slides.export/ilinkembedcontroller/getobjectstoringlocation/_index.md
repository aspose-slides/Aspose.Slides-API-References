---
title: GetObjectStoringLocation()
second_title: Aspose.Slides for C++ API Reference
description: Determines where object should be stored. This method is called once for each object id. It is not guaranteed that there won't be two objects with same data, semanticName and contentType but with different id.
type: docs
weight: 1
url: /cpp/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(**int32_t**, [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, [System::String](../../../system/string/), [System::String](../../../system/string/), [System::String](../../../system/string/)) method


Determines where object should be stored. This method is called once for each object id. It is not guaranteed that there won't be two objects with same data, semanticName and contentType but with different id.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| id | **int32_t** | Object id. This id is saving operation-wide unique. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Object binary data. This parameter can be null, if object binary data is not generated yet. |
| semanticName | [System::String](../../../system/string/) | Some short text, describing meaning of object. Controller may use this as a part of external object name, but it is up to dispatcher to ensure that names will be unique and contain only allowed characters. |
| contentType | [System::String](../../../system/string/) | MIME type of object. |
| recomendedExtension | [System::String](../../../system/string/) | File name extension, recommended for this MIME type. |

### Return Value

Decision

## See Also

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ILinkEmbedController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)
