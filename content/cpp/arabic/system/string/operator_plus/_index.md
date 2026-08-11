---
title: operator+()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: عامل ربط السلاسل.
type: docs
weight: 274
url: /ar/system/string/operator_plus/
---
## String::operator+(const String\&) const طريقة

[String](../) عامل الجمع.

```cpp
String System::String::operator+(const String &str) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) لإضافته إلى نهاية الحالي. |

### قيمة الإرجاع

سلسلة متصلة.

## String::operator+(const T\&) const طريقة

[String](../) عملية الجمع مع ثابت نصي أو مؤشر إلى سلسلة أحرف.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | أحد أشكال الثابت النصي أو مؤشر سلسلة الأحرف. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arg | const T\& | الكيان للدمج مع السلسلة الحالية. |

### قيمة الإرجاع

سلسلة متصلة.

## String::operator+(char_t) const طريقة

يضيف حرفًا إلى نهاية السلسلة.

```cpp
String System::String::operator+(char_t x) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | char_t | الحرف المراد إضافته. |

### قيمة الإرجاع

[String](../) نتيجة الجمع.

## String::operator+(int) const طريقة

يضيف تمثيل القيمة الصحيحة كسلسلة إلى نهاية السلسلة.

```cpp
String System::String::operator+(int i) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | int | القيمة الصحيحة للتحويل إلى سلسلة وإضافتها. |

### قيمة الإرجاع

[String](../) نتيجة الجمع.

## String::operator+(uint32_t) const طريقة

يضيف تمثيل القيمة الصحيحة غير الموقعة كسلسلة إلى نهاية السلسلة.

```cpp
String System::String::operator+(uint32_t i) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | **uint32_t** | القيمة للتحويل إلى سلسلة وإضافتها. |

### قيمة الإرجاع

[String](../) نتيجة الجمع.

## String::operator+(double) const طريقة

يضيف تمثيل القيمة ذات الفاصلة العائمة كسلسلة إلى نهاية السلسلة.

```cpp
String System::String::operator+(double d) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| d | **double** | القيمة للتحويل إلى سلسلة وإضافتها. |

### قيمة الإرجاع

[String](../) نتيجة الجمع.

## String::operator+(int64_t) const طريقة

يضيف تمثيل القيمة الصحيحة كسلسلة إلى نهاية السلسلة.

```cpp
String System::String::operator+(int64_t v) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| v | **int64_t** | القيمة للتحويل إلى سلسلة وإضافتها. |

### قيمة الإرجاع

[String](../) نتيجة الجمع.

## String::operator+(const T\&) const طريقة

يضيف تمثيل كائن من نوع الإشارة كسلسلة إلى نهاية السلسلة.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع المؤشر. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) لتحويله إلى سلسلة باستخدام استدعاء [ToString()](../tostring/) وإضافته إلى السلسلة الحالية. |

### قيمة الإرجاع

[String](../) نتيجة الجمع.

## String::operator+(const T\&) const طريقة

يضيف تمثيل كائن من نوع القيمة كسلسلة إلى نهاية السلسلة.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع القيمة لاستدعاء [ToString()](../tostring/) عليه. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) لتحويله إلى سلسلة باستخدام استدعاء [ToString()](../tostring/) وإضافته إلى السلسلة الحالية. |

### قيمة الإرجاع

[String](../) نتيجة الجمع.

## String::operator+(T) const طريقة

يضيف تمثيل القيمة البوليانية كسلسلة إلى نهاية السلسلة.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع القيمة للدمج مع السلسلة. يجب أن يكون bool |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) القيمة للتحويل إلى سلسلة وإضافتها. |

### قيمة الإرجاع

[String](../) نتيجة الجمع.

## انظر أيضًا

* الفئة [String](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)