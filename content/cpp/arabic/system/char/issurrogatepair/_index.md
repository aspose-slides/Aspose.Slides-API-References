---
title: IsSurrogatePair()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يحدد ما إذا كان الحرفان المحددان يشكلان زوجًا احتياطيًا في UTF-16.
type: docs
weight: 27
url: /ar/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) method

يحدد ما إذا كان الحرفان المحددان يشكلان زوجًا احتياطيًا في UTF-16.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| highSurrogate | char_t | حرف يتم اختباره لمعرفة ما إذا كان مرتفعًا (high surrogate) |
| lowSurrogate | char_t | حرف يتم اختباره لمعرفة ما إذا كان منخفضًا (low surrogate) |

### قيمة الإرجاع

True إذا كان الحرفان المحددان يشكلان زوجًا احتياطيًا، وإلا – false

## Char::IsSurrogatePair(const String\&, int) method

يحدد ما إذا كان حرفان متتاليان في المخزن المحدد يشكلان زوجًا احتياطيًا.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../../string/)\& | سلسلة |
| index | int | فهرس يبدأ من الصفر في المخزن المحدد حيث يبدأ تسلسل الأحرف المختبر |

### قيمة الإرجاع

True إذا كان الحرفان المحددان يشكلان زوجًا احتياطيًا، وإلا – false

## انظر أيضًا

* الفئة [Char](../)
* الفئة [String](../../string/)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)