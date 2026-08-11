---
title: GetObjectStoringLocation()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد المكان الذي يجب تخزين الكائن فيه. تُستدعى هذه الطريقة مرة واحدة لكل معرّف كائن. لا يوجد ضمان بعدم وجود كائنين يمتلكان نفس البيانات، semanticName و contentType ولكن بمعرّف مختلف.
type: docs
weight: 1
url: /ar/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) method


يحدد مكان تخزين الكائن. يتم استدعاء هذه الطريقة مرة واحدة لكل معرّف كائن. ليس هناك ضمان بعدم وجود كائنين يملكان نفس البيانات، semanticName و contentType ولكن بمعرّف مختلف.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```


### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| id | **int32_t** | معرّف الكائن. هذا المعرف فريد على مستوى العملية بالكامل. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بيانات الكائن الثنائية. يمكن أن تكون هذه المعاملة قيمتها null إذا لم تُنشأ بيانات الكائن الثنائية بعد. |
| semanticName | [System::String](../../../system/string/) | نص قصير يصف معنى الكائن. قد يستخدم المتحكم هذا كجزء من اسم الكائن الخارجي، لكن ذلك يعود إلى الموزّع لضمان أن تكون الأسماء فريدة وتحتوي على الأحرف المسموح بها فقط. |
| contentType | [System::String](../../../system/string/) | نوع MIME للكائن. |
| recomendedExtension | [System::String](../../../system/string/) | امتداد اسم الملف الموصى به لهذا النوع من MIME. |

### قيمة الإرجاع

القرار

## انظر أيضًا

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [ILinkEmbedController](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)