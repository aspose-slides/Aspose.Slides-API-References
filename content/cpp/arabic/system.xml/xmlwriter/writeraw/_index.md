---
title: WriteRaw()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عند إلغاء تعريفه في فئة مشتقة، يكتب التعليمات الأولية يدويًا من مخزن أحرف.
type: docs
weight: 287
url: /ar/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) طريقة

عند إلغاء تعريفها في فئة مشتقة، تقوم بكتابة التعليمات الأولية بشكل يدوي من مخزن أحرف.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | مصفوفة أحرف تحتوي على النص المراد كتابته. |
| index | **int32_t** | الموقع داخل المخزن الذي يشير إلى بداية النص المراد كتابته. |
| count | **int32_t** | عدد الأحرف التي سيتم كتابتها. |

## XmlWriter::WriteRaw(const String\&) طريقة

عند إلغاء تعريفها في فئة مشتقة، تقوم بكتابة التعليمات الأولية بشكل يدوي من سلسلة نصية.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) يحتوي على النص المراد كتابته. |

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlWriter](../)
* فئة [String](../../../system/string/)
* فضاء الأسماء [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)