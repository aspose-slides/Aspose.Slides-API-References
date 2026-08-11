---
title: Compare()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: قارن الأقل-المساوي-الأكبر بين سلسلتين فرعيتين.
type: docs
weight: 820
url: /ar/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) طريقة

قارن الأقل-المساوي-الأكبر بين سلسلتين فرعيتين.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| indexA | int | Beginning of first string substring. |
| strB | const [String](../)\& | Second string to compare. |
| indexB | int | Beginning of the second string substring. |
| length | int | Number of characters to compare. |
| ignoreCase | **bool** | Specifies whether comparison is case-insensitive. |

### قيمة الإرجاع

قيمة سالبة إذا كانت السلسلة الفرعية الأولى أصغر من الثانية، صفر إذا كانت متطابقة، وقيمة موجبة في الحالات الأخرى.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) طريقة

قارن الأقل-المساوي-الأكبر بين سلسلتين فرعيتين.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| indexA | int | Beginning of first string substring. |
| strB | const [String](../)\& | Second string to compare. |
| indexB | int | Beginning of the second string substring. |
| length | int | Number of characters to compare. |
| ignoreCase | **bool** | Specifies whether comparison is case-insensitive. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture to use for comparison. |

### قيمة الإرجاع

قيمة سالبة إذا كانت السلسلة الفرعية الأولى أصغر من الثانية، صفر إذا كانت متطابقة، وقيمة موجبة في الحالات الأخرى.

## String::Compare(const String\&, const String\&, System::StringComparison) طريقة

قارن الأقل-المساوي-الأكبر بين سلسلتين.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| strB | const [String](../)\& | Second string to compare. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### قيمة الإرجاع

قيمة سالبة إذا كانت السلسلة الفرعية الأولى أصغر من الثانية، صفر إذا كانت متطابقة، وقيمة موجبة في الحالات الأخرى.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) طريقة

قارن الأقل-المساوي-الأكبر بين سلسلتين.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| indexA | int | Beginning of first string substring. |
| strB | const [String](../)\& | Second string to compare. |
| indexB | int | Beginning of the second string substring. |
| length | int | Number of characters to compare. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### قيمة الإرجاع

قيمة سالبة إذا كانت السلسلة الفرعية الأولى أصغر من الثانية، صفر إذا كانت متطابقة، وقيمة موجبة في الحالات الأخرى.

## String::Compare(const String\&, const String\&, bool) طريقة

قارن الأقل-المساوي-الأكبر بين سلسلتين.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| strB | const [String](../)\& | Second string to compare. |
| ignoreCase | **bool** | Specifies whether comparison is case-insensitive. |

### قيمة الإرجاع

قيمة سالبة إذا كانت السلسلة الفرعية الأولى أصغر من الثانية، صفر إذا كانت متطابقة، وقيمة موجبة في الحالات الأخرى.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) طريقة

قارن الأقل-المساوي-الأكبر بين سلسلتين.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| strB | const [String](../)\& | Second string to compare. |
| ignoreCase | **bool** | Specifies whether comparison is case-insensitive. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture to use for comparison. |

### قيمة الإرجاع

قيمة سالبة إذا كانت السلسلة الفرعية الأولى أصغر من الثانية، صفر إذا كانت متطابقة، وقيمة موجبة في الحالات الأخرى.

## انظر أيضًا

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)