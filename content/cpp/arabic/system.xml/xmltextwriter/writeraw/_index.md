---
title: WriteRaw()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يكتب الترميز الخام يدويًا من مخزن مؤقت للأحرف.
type: docs
weight: 417
url: /ar/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) طريقة

يكتب الترميز الخام يدويًا من مخزن مؤقت للأحرف.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | مصفوفة أحرف تحتوي على النص المراد كتابته. |
| index | **int32_t** | الموضع داخل المصفوفة الذي يحدد بداية النص المراد كتابته. |
| count | **int32_t** | عدد الأحرف المطلوب كتابتها. |

## XmlTextWriter::WriteRaw(const String\&) طريقة

يكتب الترميز الخام يدويًا من سلسلة نصية.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) يحتوي على النص المراد كتابته. |

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlTextWriter](../)
* فئة [String](../../../system/string/)
* نطاق الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)