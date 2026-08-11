---
title: operator>>()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحصل على سلسلة من تدفق الإدخال باستخدام ترميز UTF-8.
type: docs
weight: 3004
url: /ar/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) دالة

يحصل على سلسلة من تدفق الإدخال باستخدام ترميز UTF-8.

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| in | std::istream\& | كائن تدفق إدخال (إنشاء **basic_ostream** مع **char**). |
| str | [String](../string/)\& | سلسلة تُقرأ من تدفق الإدخال. |

### قيمة الإرجاع

تدفق إدخال تم استخراج السلسلة منه.

## System::operator>>(std::wistream\&, String\&) دالة

يحصل على سلسلة من تدفق الإدخال.

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| in | std::wistream\& | كائن تدفق إدخال (إنشاء **basic_ostream** مع ****wchar_t****). |
| str | [String](../string/)\& | سلسلة تُقرأ من تدفق الإدخال. |

### قيمة الإرجاع

تدفق إدخال تم استخراج السلسلة منه.

## انظر أيضًا

* الفئة [String](../string/)
* مساحة الاسم [System](../)
* المكتبة [Aspose.Slides](../../)