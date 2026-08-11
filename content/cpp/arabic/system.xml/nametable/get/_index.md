---
title: Get()
second_title: مرجعية API لـ Aspose.Slides للغة C++
description: يرجع السلسلة المذكرة ذات القيمة المحددة.
type: docs
weight: 27
url: /ar/system.xml/nametable/get/
---
## NameTable::Get(const String\&) طريقة

يرجع السلسلة المذكرة التي لها القيمة المحددة.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```

### الوسائط

| المعيار | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | الاسم المراد العثور عليه. |

### قيمة الإرجاع

كائن السلسلة المذكرة أو **nullptr** إذا لم يتم توثيق السلسلة مسبقًا.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) طريقة

يرجع السلسلة المذكرة التي تحتوي على نفس الأحرف كما في النطاق المحدد من الأحرف في المصفوفة المعطاة.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### الوسائط

| المعيار | النوع | الوصف |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | المصفوفة الحرفية التي تحتوي على الاسم المراد العثور عليه. |
| start | **int32_t** | الفهرس الصفري داخل المصفوفة الذي يحدد الحرف الأول من الاسم. |
| len | **int32_t** | عدد الأحرف في الاسم. |

### قيمة الإرجاع

السلسلة المذكرة أو **nullptr** إذا لم يتم توثيق السلسلة مسبقًا. إذا كان **len** صفرًا، يتم إرجاع [String::Empty](../../../system/string/empty/).

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [NameTable](../)
* مساحة اسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)