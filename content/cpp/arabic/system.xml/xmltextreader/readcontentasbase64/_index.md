---
title: ReadContentAsBase64()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقرأ المحتوى ويعيد البايتات الثنائية المفكوكة من Base64.
type: docs
weight: 638
url: /ar/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) طريقة

يقرأ المحتوى ويعيد البايتات الثنائية المفكوكة من **Base64**.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن الذي سيتم نسخ النص الناتج إليه. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة داخل المخزن حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى لعدد البايتات التي ستنسخ إلى المخزن. يتم إرجاع العدد الفعلي للبايتات المنسوخة من هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات المكتوبة إلى المخزن.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [XmlTextReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)