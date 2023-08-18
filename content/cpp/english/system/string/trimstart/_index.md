---
title: TrimStart()
second_title: Aspose.Slides for C++ API Reference
description: Removes all whitespace characters from beginning of the string.
type: docs
weight: 651
url: /system/string/trimstart/
---
## String::TrimStart() const method


Removes all whitespace characters from beginning of the string.

```cpp
String System::String::TrimStart() const
```


### Return Value

[String](../) with no whitespaces at beginning.

## String::TrimStart(char_t) const method


Removes all occurrences of passed character from beginning of the string.

```cpp
String System::String::TrimStart(char_t ch) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char_t | Symbol to remove. |

### Return Value

Removal result.

## String::TrimStart(const String\&) const method


Removes all occurrences of passed characters from beginning of the string.

```cpp
String System::String::TrimStart(const String &anyOf) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) of characters to remove. |

### Return Value

[String](../) without removed characters.

## String::TrimStart(const ArrayPtr\<char_t\>\&) const method


Removes all occurrences of passed characters from beginning of the string.

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
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