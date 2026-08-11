---
title: ReadElementContentAsBase64()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بقراءة العنصر وفك تشفير محتوى Base64.
type: docs
weight: 768
url: /ar/system.xml/xmlreader/readelementcontentasbase64/
---
## XmlReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) طريقة

يقرأ العنصر ويفك تشفير محتوى **Base64**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن buffer الذي يُنسخ فيه النص الناتج. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة داخل buffer حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | العدد الأقصى للبايتات التي يجب نسخها إلى buffer. عدد البايتات الفعلي المنسوخ يُرجع من هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات المكتوبة إلى buffer.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlReader](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)