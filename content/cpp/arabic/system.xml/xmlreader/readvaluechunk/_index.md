---
title: ReadValueChunk()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بقراءة تدفقات نصية كبيرة مضمنة في مستند XML.
type: docs
weight: 807
url: /ar/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) طريقة

يقرأ تدفقات نصية كبيرة مضمنة في مستند XML.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### المعلمات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | المصفوفة من الأحرف التي تعمل كالمخزن الذي تُكتب فيه محتويات النص. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة داخل المخزن حيث يمكن للـ [XmlReader](../) أن يبدأ بنسخ النتائج. |
| count | **int32_t** | الحد الأقصى لعدد الأحرف التي يتم نسخها إلى المخزن. العدد الفعلي للأحرف المنسوخة يُرجَع من هذه الطريقة. |

### قيمة الإرجاع

عدد الأحرف التي تم قراءتها إلى المخزن. تُرجَع القيمة صفر عندما لا يكون هناك المزيد من محتوى النص.

## انظر أيضاً

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlReader](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)