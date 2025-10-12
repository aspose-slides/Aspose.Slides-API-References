---
title: Equals()
second_title: Aspose.Slides for C++ API Reference
description: String equality comparison. Several modes provided by StringComparison enumeration are supported.
type: docs
weight: 391
url: /system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const method


[String](../) equality comparison. Several modes provided by StringComparison enumeration are supported.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) to compare against the current one. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode (see [System::StringComparison](../../stringcomparison/) for details). |

### Return Value

true if strings match using selected comparison type, false otherwise.

## String::Equals(const String\&) const method


[String](../) equality comparison. Uses [System::StringComparison::Ordinal](../../stringcomparison/) comparison mode.

```cpp
bool System::String::Equals(const String &str) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) to compare against the current one. |

### Return Value

true if strings match, false otherwise.

## String::Equals(const String\&, const String\&) method


Equal-compares two strings using Ordial comparison mode.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| strB | const [String](../)\& | Second string to compare. |

### Return Value

true if strings match, false otherwise.

## String::Equals(const String\&, const String\&, System::StringComparison) method


Equal-compares two strings.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| strB | const [String](../)\& | Second string to compare. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Return Value

true if strings match, false otherwise.

## See Also

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)