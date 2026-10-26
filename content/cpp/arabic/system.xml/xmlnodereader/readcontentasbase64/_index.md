---
title: ReadContentAsBase64()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: يقرأ المحتوى ويعيد البايتات الثنائية التي تم فك ترميزها من Base64.
type: docs
weight: 443
url: /ar/system.xml/xmlnodereader/readcontentasbase64/
---
## XmlNodeReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) طريقة

يقرأ المحتوى ويعيد البايتات الثنائية التي تم فك ترميزها من Base64.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن المؤقت الذي سيتم نسخ النص الناتج إليه. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة في المخزن المؤقت حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى لعدد البايتات التي سيتم نسخها إلى المخزن المؤقت. يتم إرجاع العدد الفعلي للبايتات المنسوخة من هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات المكتوبة في المخزن المؤقت.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlNodeReader](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)