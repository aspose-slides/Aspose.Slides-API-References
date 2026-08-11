---
title: CopyTo()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "ينسخ عناصر ICollection إلى System::Array، بدءًا من فهرس System::Array معين."
type: docs
weight: 105
url: /ar/aspose.slides/paragraphcollection/copyto/
---
## ParagraphCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IParagraph\>\>, int32_t) طريقة

ينسخ عناصر [ICollection](../../../system.collections.generic/icollection/) إلى [System::Array](../../../system/array/)، بدءًا من فهرس [System::Array](../../../system/array/) معين.

```cpp
void Aspose::Slides::ParagraphCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IParagraph>> array, int32_t arrayIndex)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\>\> | المصفوفة الأحادية البُعد [System::Array](../../../system/array/) التي هي مقصد العناصر المنسوخة من [ICollection](../../../system.collections.generic/icollection/). يجب أن تكون [System::Array](../../../system/array/) ذات فهرسة تبدأ من الصفر. |
| arrayIndex | **int32_t** | الفهرس الذي يبدأ من الصفر في *array* حيث يبدأ النسخ. |

## انظر أيضًا

* نوع معرف [ArrayPtr](../../../system/arrayptr/)
* نوع معرف [SharedPtr](../../../system/sharedptr/)
* فئة [IParagraph](../../iparagraph/)
* فئة [ParagraphCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)