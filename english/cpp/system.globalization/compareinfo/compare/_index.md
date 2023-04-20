---
title: Compare()
second_title: Aspose.Slides for C++ API Reference
description: Compares strings. Not implemented.
type: docs
weight: 66
url: /cpp/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const method


Compares strings. Not implemented.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | LHS string. |
| string2 | const [String](../../../system/string/)\& | RHS string. |

### Return Value

Negative value if LHS string preceeds RHS one, zero if they match, positive value otherwise.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const method


Compares strings. Only Ordinal and OrdinalIgnoreCase modes are supported.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | LHS string. |
| b | const [String](../../../system/string/)\& | RHS string. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) comparison type. |

### Return Value

Negative value if LHS string preceeds RHS one, zero if they match, positive value otherwise.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const method


Compares a section of one string with a section of second string. Not implemented.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | First string. |
| offset1 | int | Start index of characters in **string1**. |
| length1 | int | Number of characters in **string1** to compare. |
| string2 | const [String](../../../system/string/)\& | Second string. |
| offset2 | int | Start index of characters in **string2**. |
| length2 | int | Number of characters in **string2** to compare. |

### Return Value

Negative value if first string section preceeds second string section, zero if they match, positive value otherwise.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const method


Compares the end section of one string with the end section of second string using string comparison methods. Not implemented.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | First string. |
| offset1 | int | Start index of characters in **string1**. |
| string2 | const [String](../../../system/string/)\& | Second string. |
| offset2 | int | Start index of characters in **string2**. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) comparison options. |

### Return Value

Negative value if first string section preceeds second string section, zero if they match, positive value otherwise.

## CompareInfo::Compare(const String\&, int, const String\&, int) const method


Compares the end section of one string with the end section of second string. Not implemented.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | First string. |
| offset1 | int | Start index of characters in **string1**. |
| string2 | const [String](../../../system/string/)\& | Second string. |
| offset2 | int | Start index of characters in **string2**. |

### Return Value

Negative value if first string section preceeds second string section, zero if they match, positive value otherwise.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const method


Compares a section of one string with a section of second string using string comparison methods. Not implemented.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | First string. |
| offset1 | int | Start index of characters in **string1**. |
| length1 | int | Number of characters in **string1** to compare. |
| string2 | const [String](../../../system/string/)\& | Second string. |
| offset2 | int | Start index of characters in **string2**. |
| length2 | int | Number of characters in **string2** to compare. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) comparison options. |

### Return Value

Negative value if first string section preceeds second string section, zero if they match, positive value otherwise.

## See Also

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)