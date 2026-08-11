---
title: ReadContentAsBase64()
second_title: Aspose.Slides للغة C++ مرجع API
description: يقرأ المحتوى ويعيد البايتات الثنائية التي تم فك ترميزها من Base64.
type: docs
weight: 755
url: /ar/system.xml/xmlreader/readcontentasbase64/
---
## XmlReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) طريقة

تقرأ المحتوى وتعيد البايتات الثنائية التي تم فك ترميزها من Base64.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن المؤقت الذي تُنسخ إليه النص الناتج. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة داخل المخزن المؤقت حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى لعدد البايتات التي سيتم نسخها إلى المخزن المؤقت. يتم إرجاع العدد الفعلي للبايتات المنسوخّة من هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات المكتوبة إلى المخزن المؤقت.

## انظر أيضًا

* نوع تعريف [ArrayPtr](../../../system/arrayptr/)
* الفئة [XmlReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)