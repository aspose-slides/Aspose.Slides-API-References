---
title: Get()
second_title: مرجع API Aspose.Slides للغة C++
description: عندما يتم تجاوزها في فئة مشتقة، يحصل على السلسلة المؤلفة من الذرات التي تحتوي على نفس الأحرف كما هو محدد في النطاق المعطى من الأحرف في المصفوفة.
type: docs
weight: 1
url: /ar/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) طريقة


عند تجاوزها في فئة مشتقة، تحصل على السلسلة المؤلفة من الذرات التي تحتوي على نفس الأحرف كما في النطاق المحدد من الأحرف في المصفوفة المعطاة.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### المعطيات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | مصفوفة الأحرف التي تحتوي على الاسم المراد البحث عنه. |
| offset | **int32_t** | الفهرس الصفري إلى داخل المصفوفة الذي يحدد أول حرف من الاسم. |
| length | **int32_t** | عدد الأحرف في الاسم. |

### قيمة الإرجاع

السلسلة المؤلفة من الذرات أو **nullptr** إذا لم يتم تأليف السلسلة مسبقًا. إذا كان **length** صفرًا، يتم إرجاع [String::Empty](../../../system/string/empty/).

## XmlNameTable::Get(const String\&) طريقة


عند تجاوزها في فئة مشتقة، تحصل على السلسلة المؤلفة من الذرات التي تحتوي على نفس القيمة كما في السلسلة المحددة.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


### المعطيات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | الاسم المراد البحث عنه. |

### قيمة الإرجاع

السلسلة المؤلفة من الذرات أو **nullptr** إذا لم يتم تأليف السلسلة مسبقًا.

## راجع أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* صف [String](../../../system/string/)
* صف [XmlNameTable](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)