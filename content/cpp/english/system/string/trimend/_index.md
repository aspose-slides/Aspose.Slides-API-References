---
title: TrimEnd()
second_title: Aspose.Slides for C++ API Reference
description: Removes all whitespace characters from end of the string.
type: docs
weight: 690
url: /system/string/trimend/
---
## String::TrimEnd() const method


Removes all whitespace characters from end of the string.

```cpp
String System::String::TrimEnd() const
```


### Return Value

[String](../) with no whitespaces at beginning.

## String::TrimEnd(char_t) const method


Removes all occurrences of passed character from end of the string.

```cpp
String System::String::TrimEnd(char_t ch) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char_t | Symbol to remove. |

### Return Value

Removal result.

## String::TrimEnd(const String\&) const method


Removes all occurrences of passed characters from end of the string.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) of characters to remove. |

### Return Value

[String](../) without removed characters.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const method


Removes all occurrences of passed characters from end of the string.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
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