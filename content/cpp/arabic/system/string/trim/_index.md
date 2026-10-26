---
title: Trim()
second_title: مرجع API Aspose.Slides للغة C++
description: يزيل جميع أحرف الفراغ من بداية ونهاية السلسلة.
type: docs
weight: 677
url: /ar/system/string/trim/
---
## String::Trim() const طريقة

يزيل جميع أحرف المسافات البيضاء من بداية ونهاية السلسلة.

```cpp
String System::String::Trim() const
```

### قيمة الإرجاع

[String](../) بدون مسافات بيضاء في البداية أو النهاية.

## String::Trim(char_t) const طريقة

يزيل جميع تكرارات الحرف الممرَّر من بداية ونهاية السلسلة.

```cpp
String System::String::Trim(char_t ch) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ch | char_t | الرمز لإزالته. |

### قيمة الإرجاع

نتيجة الإزالة.

## String::Trim(const String\&) const طريقة

يزيل جميع تكرارات الأحرف الممرَّرة من بداية ونهاية السلسلة.

```cpp
String System::String::Trim(const String &anyOf) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) من الأحرف لإزالتها. |

### قيمة الإرجاع

[String](../) بدون الأحرف المُزالة.

## String::Trim(const ArrayPtr\<char_t\>\&) const طريقة

يزيل جميع تكرارات الأحرف الممرَّرة من بداية ونهاية السلسلة.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) من الأحرف لإزالتها. |

### قيمة الإرجاع

[String](../) بدون الأحرف المُزالة.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* فئة [String](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)