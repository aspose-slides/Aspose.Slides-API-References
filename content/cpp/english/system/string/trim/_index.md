---
title: Trim()
second_title: Aspose.Slides for C++ API Reference
description: Removes all whitespace characters from both beginning and end of the string.
type: docs
weight: 638
url: /system/string/trim/
---
## String::Trim() const method


Removes all whitespace characters from both beginning and end of the string.

```cpp
String System::String::Trim() const
```


### Return Value

[String](../) with no whitespaces at beginning or end.

## String::Trim(char_t) const method


Removes all occurrences of passed character from both beginning and end of the string.

```cpp
String System::String::Trim(char_t ch) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char_t | Symbol to remove. |

### Return Value

Removal result.

## String::Trim(const String\&) const method


Removes all occurrences of passed characters from both beginning and end of the string.

```cpp
String System::String::Trim(const String &anyOf) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) of characters to remove. |

### Return Value

[String](../) without removed characters.

## String::Trim(const ArrayPtr\<char_t\>\&) const method


Removes all occurrences of passed characters from both beginning and end of the string.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) of characters to remove. |

### Return Value

[String](../) without removed characters.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)