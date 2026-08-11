---
title: PrintToString()
second_title: Aspose.Slides لتوثيق API للغة C++
description: يطبع الكائن إلى سلسلة باختيار دالة التسلسل المناسبة.
type: docs
weight: 1
url: /ar/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T&) دالة

يطبع الكائن إلى سلسلة باختيار دالة التسلسل المناسبة.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | [Object](../../system/object/) نوع. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) للطباعة. |

### قيمة الإرجاع

[String](../../system/string/) تمثيلات الكائن الممرَّ.

## System::TestPredicates::Details::PrintToString(const T&) دالة

يطبع حاويات على نمط ICollection إلى سلسلة عن طريق طباعة عناصرها (لا أكثر من 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | [Object](../../system/object/) نوع. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) للطباعة. |

### قيمة الإرجاع

تمثيلات السلسلة المشتركة للعناصر المحتواة.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) دالة

يطبع nullptr إلى سلسلة.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### قيمة الإرجاع

سلسلة "nullptr".

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) دالة

يطبع مجموعات [IEnumerable<bool>](../../system.collections.generic/ienumerable/) إلى سلسلة عن طريق طباعة عناصرها (لا أكثر من 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | [Object](../../system/object/) نوع. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) للطباعة. |

### قيمة الإرجاع

تمثيلات السلسلة المشتركة للعناصر المحتواة.

## أنظر أيضًا

* فئة [IEnumerable](../../system.collections.generic/ienumerable/)
* بنية [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* مساحة اسم [System::TestPredicates::Details](../)
* مكتبة [Aspose.Slides](../../)