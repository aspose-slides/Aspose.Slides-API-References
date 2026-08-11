---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بقراءة العنصر ويفك شفرة محتوى Base64.
type: docs
weight: 469
url: /ar/system.xml/xmlnodereader/readelementcontentasbase64/
---
## XmlNodeReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) طريقة

يقرأ العنصر ويفك تشفير محتوى Base64.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن المؤقت الذي يُنسخ إليه النص الناتج. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة داخل المخزن المؤقت حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى للبايتات التي يتم نسخها إلى المخزن المؤقت. عدد البايتات الفعلي المنسوخة يُعاد من هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات المكتوبة إلى المخزن المؤقت.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlNodeReader](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)