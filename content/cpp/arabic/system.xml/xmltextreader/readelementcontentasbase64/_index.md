---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides للـ C++ – مرجع API
description: يقرأ العنصر ويفك تشفير محتوى Base64.
type: docs
weight: 651
url: /ar/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

يقرأ العنصر ويفك تشفير المحتوى بصيغة Base64.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن المؤقت الذي تُنسخ فيه النص الناتج. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة في المخزن المؤقت حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى لعدد البايتات التي سيتم نسخها إلى المخزن المؤقت. عدد البايتات الفعلي المنسوخ يُعاد بواسطة هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات المكتوبة إلى المخزن المؤقت.

## انظر أيضاً

* نوع معرف [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlTextReader](../)
* مساحة اسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)