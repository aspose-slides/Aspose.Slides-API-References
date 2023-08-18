---
title: GetNumericValue()
second_title: Aspose.Slides for C++ API Reference
description: Gets numeric value associated with the specified character.
type: docs
weight: 27
url: /system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) method


Gets numeric value associated with the specified character.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char16_t | Unicode character. |

### Return Value

The numeric value or -1 if the specified character is not a numeric character.

## CharUnicodeInfo::GetNumericValue(const String\&, int) method


Gets numeric value associated with the character at the specified index of the string.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | The string containing unicode character. |
| index | int | The index of the unicode character. |

### Return Value

The numeric value or -1 if the specified character is not a numeric character.

## See Also

* Class [CharUnicodeInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)