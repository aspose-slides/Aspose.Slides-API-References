---
title: CompareOrdinal()
second_title: Aspose.Slides for C++ API Reference
description: Less-equal-greater-compares two strings using ordinal mode.
type: docs
weight: 820
url: /system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) method


Less-equal-greater-compares two strings using ordinal mode.

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| strB | const [String](../)\& | Second string to compare. |

### Return Value

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## String::CompareOrdinal(const String\&, int, const String\&, int, int) method


Less-equal-greater-compares two strings using ordinal mode.

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | First string to compare. |
| indexA | int | Beginning of first string substring. |
| strB | const [String](../)\& | Second string to compare. |
| indexB | int | Beginning of the second string substring. |
| length | int | Number of characters to compare. |

### Return Value

Negative value if first substring is less then second, zero if they match, positive value otherwise.

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)