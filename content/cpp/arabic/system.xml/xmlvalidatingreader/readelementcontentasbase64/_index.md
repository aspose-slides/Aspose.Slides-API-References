---
title: ReadElementContentAsBase64()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بقراءة العنصر وفك ترميز محتوى Base64.
type: docs
weight: 586
url: /ar/system.xml/xmlvalidatingreader/readelementcontentasbase64/
---
## XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

يقوم بقراءة العنصر وفك ترميز محتوى Base64.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن المؤقت الذي يتم نسخ النص الناتج إليه. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة داخل المخزن المؤقت حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى لعدد البايتات التي سيتم نسخها إلى المخزن المؤقت. يتم إرجاع عدد البايتات الفعلي الذي تم نسخه من هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات التي تم كتابتها إلى المخزن المؤقت.

## انظر أيضا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlValidatingReader](../)
* نطاق الأسماء [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)