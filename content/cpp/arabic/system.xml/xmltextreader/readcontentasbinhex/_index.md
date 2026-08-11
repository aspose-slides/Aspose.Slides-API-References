---
title: ReadContentAsBinHex()
second_title: مرجع API ل Aspose.Slides للغة C++
description: يقرأ المحتوى ويعيد البايتات الثنائية المشفّرة بنظام BinHex.
type: docs
weight: 664
url: /ar/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) طريقة

يقرأ المحتوى ويعيد بايتات البايناري المشفّرة بنظام **BinHex**.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن الذي سيتم نسخ النص الناتج إليه. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة داخل المخزن حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى لعدد البايتات التي سيتم نسخها إلى المخزن. يتم إرجاع العدد الفعلي للبايتات المنسوخة من هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات التي تم كتابتها إلى المخزن.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlTextReader](../)
* نطاق الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)