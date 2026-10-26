---
title: ReadElementContentAsBinHex()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بقراءة العنصر وفك تشفير محتوى BinHex.
type: docs
weight: 794
url: /ar/system.xml/xmlreader/readelementcontentasbinhex/
---
## XmlReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) طريقة

يقوم بقراءة العنصر وفك تشفير محتوى **BinHex**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن المؤقت الذي تُنسخ إليه النص الناتج. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة في المخزن المؤقت حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى لعدد البايتات التي سيتم نسخها إلى المخزن المؤقت. يتم إرجاع عدد البايتات الفعلي المنسوخة من هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات التي تم كتابتها إلى المخزن المؤقت.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlReader](../)
* مساحة أسماء [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)