---
title: ReadContentAsBase64()
second_title: Aspose.Slides لمرجع API C++
description: يقوم بقراءة المحتوى ويعيد البايتات الثنائية المفكوكة من Base64.
type: docs
weight: 573
url: /ar/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidtingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) طريقة

يقرأ المحتوى ويعيد بايتات البيانات الثنائية المشفّرة بترميز Base64.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن المؤقت الذي يُنسخ إليه النص الناتج. لا يمكن أن يكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة داخل المخزن المؤقت حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | العدد الأقصى للبايتات التي سيُنسخ إلى المخزن المؤقت. يتم إرجاع العدد الفعلي للبايتات المنسوخة من هذه الدالة. |

### قيمة الإرجاع

عدد البايتات المكتوبة إلى المخزن المؤقت.

## أنظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlValidatingReader](../)
* مساحة اسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)