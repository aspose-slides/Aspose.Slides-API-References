---
title: Equals()
second_title: Aspose.Slides لـ C++ مرجع API
description: مقارنة مساواة السلاسل. يتم دعم عدة أوضاع يقدمها تعداد StringComparison.
type: docs
weight: 391
url: /ar/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const طريقة

[String](../) مقارنة مساواة. يتم دعم عدة أوضاع يوفرها تعداد StringComparison.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) للمقارنة مع الحالي. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) الوضع (انظر [System::StringComparison](../../stringcomparison/) للتفاصيل). |

### قيمة الإرجاع

صحيح إذا كانت السلاسل متطابقة باستخدام نوع المقارنة المحدد، وإلا خاطئ.

## String::Equals(const String\&) const طريقة

[String](../) مقارنة مساواة. يستخدم وضع المقارنة [System::StringComparison::Ordinal](../../stringcomparison/).

```cpp
bool System::String::Equals(const String &str) const
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) للمقارنة مع الحالي. |

### قيمة الإرجاع

صحيح إذا كانت السلاسل متطابقة، وإلا خاطئ.

## String::Equals(const String\&, const String\&) طريقة

يقارن بين سلسلتين باستخدام وضع المقارنة Ordial.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| strA | const [String](../)\& | السلسلة الأولى للمقارنة. |
| strB | const [String](../)\& | السلسلة الثانية للمقارنة. |

### قيمة الإرجاع

صحيح إذا كانت السلاسل متطابقة، وإلا خاطئ.

## String::Equals(const String\&, const String\&, System::StringComparison) طريقة

يقارن بين سلسلتين.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| strA | const [String](../)\& | السلسلة الأولى للمقارنة. |
| strB | const [String](../)\& | السلسلة الثانية للمقارنة. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) الوضع. |

### قيمة الإرجاع

صحيح إذا كانت السلاسل متطابقة، وإلا خاطئ.

## انظر أيضًا

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)