---
title: TrimEnd()
second_title: Aspose.Slides لـ C++ مرجع API
description: يزيل جميع أحرف المسافات البيضاء من نهاية السلسلة.
type: docs
weight: 703
url: /ar/system/string/trimend/
---
## String::TrimEnd() const طريقة

يزيل جميع أحرف المسافات البيضاء من نهاية السلسلة.

```cpp
String System::String::TrimEnd() const
```

### قيمة الإرجاع

[String](../) بدون مسافات في البداية.

## String::TrimEnd(char_t) const طريقة

يزيل جميع تكرارات الحرف الممرَّر من نهاية السلسلة.

```cpp
String System::String::TrimEnd(char_t ch) const
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ch | char_t | الرمز الذي يتم إزالته. |

### قيمة الإرجاع

نتيجة الإزالة.

## String::TrimEnd(const String\&) const طريقة

يزيل جميع تكرارات الأحرف الممرَّرة من نهاية السلسلة.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) من الأحرف التي يجب إزالتها. |

### قيمة الإرجاع

[String](../) بدون الأحرف التي تمت إزالتها.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const طريقة

يزيل جميع تكرارات الأحرف الممرَّرة من نهاية السلسلة.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) من الأحرف التي يجب إزالتها. |

### قيمة الإرجاع

[String](../) بدون الأحرف التي تمت إزالتها.

## انظر أيضًا

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)