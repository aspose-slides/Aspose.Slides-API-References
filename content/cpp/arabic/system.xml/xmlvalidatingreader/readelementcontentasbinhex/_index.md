---
title: ReadElementContentAsBinHex()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بقراءة العنصر وفك ترميز محتوى BinHex.
type: docs
weight: 612
url: /ar/system.xml/xmlvalidatingreader/readelementcontentasbinhex/
---
## XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) طريقة

يقوم بقراءة العنصر وفك ترميز محتوى BinHex.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن الذي يتم نسخ النص الناتج إليه. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة في المخزن حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى لعدد البايتات التي سيتم نسخها إلى المخزن. يتم إرجاع العدد الفعلي للبايتات المنسوخة من هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات المكتوبة إلى المخزن.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)