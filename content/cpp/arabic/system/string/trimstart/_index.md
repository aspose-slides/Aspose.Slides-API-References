---
title: TrimStart()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يزيل جميع أحرف المسافات البيضاء من بداية السلسلة.
type: docs
weight: 690
url: /ar/system/string/trimstart/
---
## String::TrimStart() const طريقة

Removes all whitespace characters from beginning of the string.

```cpp
String System::String::TrimStart() const
```

### قيمة الإرجاع

[String](../) بدون مسافات بيضاء في البداية.

## String::TrimStart(char_t) const طريقة

Removes all occurrences of passed character from beginning of the string.

```cpp
String System::String::TrimStart(char_t ch) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ch | char_t | الرمز المراد إزالته. |

### قيمة الإرجاع

نتيجة الإزالة.

## String::TrimStart(const String\&) const طريقة

Removes all occurrences of passed characters from beginning of the string.

```cpp
String System::String::TrimStart(const String &anyOf) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) من الأحرف لإزالتها. |

### قيمة الإرجاع

[String](../) بدون الأحرف التي أزيلت.

## String::TrimStart(const ArrayPtr\<char_t\>\&) const طريقة

Removes all occurrences of passed characters from beginning of the string.

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) من الأحرف لإزالتها. |

### قيمة الإرجاع

[String](../) بدون الأحرف التي أزيلت.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* فئة [String](../)
* مساحة الأسماء [System](../../)
* مكتبة [Aspose.Slides](../../../)