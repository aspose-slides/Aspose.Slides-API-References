---
title: Concat()
second_title: مرجع API Aspose.Slides للغة C++
description: يجمع مصفوفة السلاسل.
type: docs
weight: 1
url: /ar/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) دالة

يجمع مصفوفة السلاسل.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) من السلاسل للانضمام. |

### قيمة الإرجاع

السلسلة المدمجة.

## System::StringExtra::Concat(const String\&, const String\&) دالة

يجمع السلاسل.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | السلسلة الأولى للدمج. |
| str1 | const [String](../../system/string/)\& | السلسلة الثانية للدمج. |

### قيمة الإرجاع

السلاسل المدمجة للمعاملات.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) دالة

يجمع السلاسل.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | السلسلة الأولى للدمج. |
| str1 | const [String](../../system/string/)\& | السلسلة الثانية للدمج. |
| str2 | const [String](../../system/string/)\& | السلسلة الثالثة للدمج. |

### قيمة الإرجاع

السلاسل المدمجة للمعاملات.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) دالة

يجمع السلاسل.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | السلسلة الأولى للدمج. |
| str1 | const [String](../../system/string/)\& | السلسلة الثانية للدمج. |
| str2 | const [String](../../system/string/)\& | السلسلة الثالثة للدمج. |
| str3 | const [String](../../system/string/)\& | السلسلة الرابعة للدمج. |

### قيمة الإرجاع

السلاسل المدمجة للمعاملات.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) دالة

يحوّل عدة كائنات إلى سلسلة ويجمع السلاسل الناتجة. تخصيص لأنواع [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) للتحويل والدمج. |

### قيمة الإرجاع

[String](../../system/string/) القيمة المدمجة من تمثيلات السلاسل لجميع الكائنات الممررة.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) دالة

يحوّل عدة كائنات إلى سلسلة ويجمع السلاسل الناتجة. تخصيص لأنواع حسابية.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) للتحويل والدمج. |

### قيمة الإرجاع

[String](../../system/string/) القيمة المدمجة من تمثيلات السلاسل لجميع الكائنات الممررة.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) دالة

يحوّل عدة كائنات إلى سلسلة ويجمع السلاسل الناتجة. تخصيص للهياكل وأنواع القيمة الأخرى.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) للتحويل والدمج. |

### قيمة الإرجاع

[String](../../system/string/) القيمة المدمجة من تمثيلات السلاسل لجميع الكائنات الممررة.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../system/arrayptr/)
* فئة [String](../../system/string/)
* بنية [IsSmartPtr](../../system/issmartptr/)
* مساحة الاسم [System::StringExtra](../)
* مكتبة [Aspose.Slides](../../)