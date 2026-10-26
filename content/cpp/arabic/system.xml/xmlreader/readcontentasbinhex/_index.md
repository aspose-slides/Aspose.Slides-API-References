---
title: ReadContentAsBinHex()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بقراءة المحتوى ويعيد البايتات الثنائية التي تم فك تشفيرها بتقنية BinHex.
type: docs
weight: 781
url: /ar/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) طريقة

يقرأ المحتوى ويعيد بايتات ثنائية تم فك تشفيرها بتقنية **BinHex**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن المؤقت الذي تُنسَخ إليه النص الناتج. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة في المخزن المؤقت حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى لعدد البايتات التي سيتم نسخها إلى المخزن المؤقت. يتم إرجاع العدد الفعلي للبايتات المنسوخة من هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات التي كُتبت إلى المخزن المؤقت.

## انظر أيضاً

* تعريف النوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlReader](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)