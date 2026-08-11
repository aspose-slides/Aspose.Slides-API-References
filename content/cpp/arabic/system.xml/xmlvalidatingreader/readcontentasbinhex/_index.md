---
title: ReadContentAsBinHex()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقرأ المحتوى ويُعيد البايتات الثنائية المفكوكة من BinHex.
type: docs
weight: 599
url: /ar/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) طريقة

يقرأ المحتوى ويُعيد البايتات الثنائية المفكوكة من BinHex.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن المؤقت الذي ستُنسخ إليه النص الناتج. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة داخل المخزن المؤقت حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى لعدد البايتات التي سيتم نسخها إلى المخزن المؤقت. يتم إرجاع عدد البايتات الفعلي المنسوخة من هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات المكتوبة إلى المخزن المؤقت.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlValidatingReader](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)