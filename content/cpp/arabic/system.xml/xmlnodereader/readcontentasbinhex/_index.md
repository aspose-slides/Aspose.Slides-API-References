---
title: ReadContentAsBinHex()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقرأ المحتوى ويعيد بايتات الثنائي التي تم فك تشفيرها من BinHex.
type: docs
weight: 456
url: /ar/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) طريقة

يقرأ المحتوى ويعيد بايتات الثنائية التي تم فك تشفيرها من BinHex.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن المؤقت الذي يُنسخ إليه النص الناتج. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة داخل المخزن المؤقت حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى لعدد البايتات التي تُنسخ إلى المخزن المؤقت. عدد البايتات الفعلي التي تم نسخها يُعاد من هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات المكتوبة إلى المخزن المؤقت.

## انظر أيضا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlNodeReader](../)
* مساحة اسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)