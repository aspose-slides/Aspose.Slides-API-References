---
title: Compare()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقارن السلاسل. غير مُنفّذ.
type: docs
weight: 66
url: /ar/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const طريقة

يقارن السلاسل. غير مُنفّذ.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | سلسلة LHS. |
| string2 | const [String](../../../system/string/)\& | سلسلة RHS. |

### قيمة الإرجاع

قيمة سلبية إذا كانت سلسلة LHS تسبق سلسلة RHS، صفر إذا كانت متطابقة، قيمة إيجابية خلاف ذلك.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const طريقة

يقارن السلاسل. تدعم فقط أوضاع Ordinal و OrdinalIgnoreCase.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | سلسلة LHS. |
| b | const [String](../../../system/string/)\& | سلسلة RHS. |
| options | [CompareOptions](../../compareoptions/) | نوع مقارنة [String](../../../system/string/). |

### قيمة الإرجاع

قيمة سلبية إذا كانت سلسلة LHS تسبق سلسلة RHS، صفر إذا كانت متطابقة، قيمة إيجابية خلاف ذلك.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const طريقة

يقارن جزءًا من سلسلة مع جزء من سلسلة أخرى. غير مُنفّذ.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | السلسلة الأولى. |
| offset1 | int | فهرس البداية للأحرف في **string1**. |
| length1 | int | عدد الأحرف في **string1** للمقارنة. |
| string2 | const [String](../../../system/string/)\& | السلسلة الثانية. |
| offset2 | int | فهرس البداية للأحرف في **string2**. |
| length2 | int | عدد الأحرف في **string2** للمقارنة. |

### قيمة الإرجاع

قيمة سلبية إذا كان جزء السلسلة الأولى يسبق جزء السلسلة الثانية، صفر إذا كانا متطابقين، قيمة إيجابية خلاف ذلك.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const طريقة

يقارن الجزء النهائي من سلسلة مع الجزء النهائي من سلسلة أخرى باستخدام طرق مقارنة السلاسل. غير مُنفّذ.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | السلسلة الأولى. |
| offset1 | int | فهرس البداية للأحرف في **string1**. |
| string2 | const [String](../../../system/string/)\& | السلسلة الثانية. |
| offset2 | int | فهرس البداية للأحرف في **string2**. |
| options | [CompareOptions](../../compareoptions/) | خيارات مقارنة [String](../../../system/string/). |

### قيمة الإرجاع

قيمة سلبية إذا كان جزء السلسلة الأولى يسبق جزء السلسلة الثانية، صفر إذا كانا متطابقين، قيمة إيجابية خلاف ذلك.

## CompareInfo::Compare(const String\&, int, const String\&, int) const طريقة

يقارن الجزء النهائي من سلسلة مع الجزء النهائي من سلسلة أخرى. غير مُنفّذ.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | السلسلة الأولى. |
| offset1 | int | فهرس البداية للأحرف في **string1**. |
| string2 | const [String](../../../system/string/)\& | السلسلة الثانية. |
| offset2 | int | فهرس البداية للأحرف في **string2**. |

### قيمة الإرجاع

قيمة سلبية إذا كان جزء السلسلة الأولى يسبق جزء السلسلة الثانية، صفر إذا كانا متطابقين، قيمة إيجابية خلاف ذلك.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const طريقة

يقارن جزءًا من سلسلة مع جزء من سلسلة أخرى باستخدام طرق مقارنة السلاسل. غير مُنفّذ.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | السلسلة الأولى. |
| offset1 | int | فهرس البداية للأحرف في **string1**. |
| length1 | int | عدد الأحرف في **string1** للمقارنة. |
| string2 | const [String](../../../system/string/)\& | السلسلة الثانية. |
| offset2 | int | فهرس البداية للأحرف في **string2**. |
| length2 | int | عدد الأحرف في **string2** للمقارنة. |
| options | [CompareOptions](../../compareoptions/) | خيارات مقارنة [String](../../../system/string/). |

### قيمة الإرجاع

قيمة سلبية إذا كان جزء السلسلة الأولى يسبق جزء السلسلة الثانية، صفر إذا كانا متطابقين، قيمة إيجابية خلاف ذلك.

## أنظر أيضًا

* التعداد [CompareOptions](../../compareoptions/)
* الفئة [String](../../../system/string/)
* الفئة [CompareInfo](../)
* النطاق [System::Globalization](../../)
* المكتبة [Aspose.Slides](../../../)