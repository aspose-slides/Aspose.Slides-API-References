---
title: Compare()
second_title: Aspose.Slides for C++ API Reference
description: Less-equal-greater-compares two substrings.
type: docs
weight: 781
url: /cpp/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) method


Less-equal-greater-compares two substrings.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| indexA | int | Beginning of first string substring. |
| strB | const [String](../)\& | Second string to compare. |
| indexB | int | Beginning of the second string substring. |
| length | int | Number of characters to compare. |
| ignoreCase | **bool** | Specifies whether comparison is case-insensitive. |

### Return Value

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) method


Less-equal-greater-compares two substrings.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| indexA | int | Beginning of first string substring. |
| strB | const [String](../)\& | Second string to compare. |
| indexB | int | Beginning of the second string substring. |
| length | int | Number of characters to compare. |
| ignoreCase | **bool** | Specifies whether comparison is case-insensitive. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture to use for comparison. |

### Return Value

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## String::Compare(const String\&, const String\&, System::StringComparison) method


Less-equal-greater-compares two strings.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| strB | const [String](../)\& | Second string to compare. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Return Value

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) method


Less-equal-greater-compares two strings.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| indexA | int | Beginning of first string substring. |
| strB | const [String](../)\& | Second string to compare. |
| indexB | int | Beginning of the second string substring. |
| length | int | Number of characters to compare. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Return Value

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## String::Compare(const String\&, const String\&, bool) method


Less-equal-greater-compares two strings.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| strB | const [String](../)\& | Second string to compare. |
| ignoreCase | **bool** | Specifies whether comparison is case-insensitive. |

### Return Value

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) method


Less-equal-greater-compares two strings.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| strB | const [String](../)\& | Second string to compare. |
| ignoreCase | **bool** | Specifies whether comparison is case-insensitive. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture to use for comparison. |

### Return Value

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## See Also

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)