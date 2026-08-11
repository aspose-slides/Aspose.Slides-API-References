---
title: ReadElementContentAsBinHex()
second_title: مرجع API الخاص بـ Aspose.Slides للـ C++
description: يقرأ العنصر ويفكّ شفرة محتوى BinHex.
type: docs
weight: 677
url: /ar/system.xml/xmltextreader/readelementcontentasbinhex/
---
## XmlTextReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


يقرأ العنصر ويفكّ شفرة محتوى **BinHex**.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن المؤقت الذي تُنسخ إليه النص الناتج. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة في المخزن المؤقت حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى لعدد البايتات التي يتم نسخها إلى المخزن المؤقت. يتم إرجاع العدد الفعلي للبايتات المنسوخة من هذا الأسلوب. |

### قيمة الإرجاع

عدد البايتات المكتوبة إلى المخزن المؤقت.

## انظر أيضا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlTextReader](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)