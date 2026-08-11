---
title: Add()
second_title: مرجع API Aspose.Slides للغة C++
description: عند تجاوزها في فئة مشتقة، تقوم بأتمتة السلسلة المحددة وتضيفها إلى XmlNameTable.
type: docs
weight: 14
url: /ar/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) طريقة

عند تجاوزها في فئة مشتقة، تقوم بأتمتة السلسلة المحددة وتضيفها إلى [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | مصفوفة الأحرف التي تحتوي على الاسم المراد إضافته. |
| offset | **int32_t** | الفهرس المستند إلى الصفر في المصفوفة يحدّد أول حرف من الاسم. |
| length | **int32_t** | عدد الأحرف في الاسم. |

### القيمة المرجعة

السلسلة الأتومية الجديدة أو السلسلة الحالية إذا كانت موجودة بالفعل. إذا كان الطول صفرًا، يتم إرجاع [String::Empty](../../../system/string/empty/).

## XmlNameTable::Add(const String\&) طريقة

عند تجاوزها في فئة مشتقة، تقوم بأتمتة السلسلة المحددة وتضيفها إلى [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | الاسم لإضافته. |

### القيمة المرجعة

السلسلة الأتومية الجديدة أو السلسلة الحالية إذا كانت موجودة بالفعل.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [XmlNameTable](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)