---
title: Insert()
second_title: Aspose.Slides for C++ API Reference
description: Inserts string into builder's fixed position.
type: docs
weight: 170
url: /system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) method


Inserts string into builder's fixed position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Position to insert characters into. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) to insert. |

### Return Value

This pointer.

## StringBuilder::Insert(int32_t, const String\&, int32_t) method


Inserts repeated string into builder's fixed position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position to insert characters into. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) to insert. |
| count | **int32_t** | How many times to repeat **value** string. |

### Return Value

This pointer.

## StringBuilder::Insert(int, char_t) method


Inserts character into builder's fixed position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Position to insert characters into. |
| ch | char_t | Character to insert. |

### Return Value

This pointer.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) method


Inserts characters into builder's fixed position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert characters into. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) to insert slice from. |
| startIndex | int | [Array](../../../system/array/) slice beginning index. |
| charCount | int | [Array](../../../system/array/) slice length. |

### Return Value

This pointer.

## StringBuilder::Insert(int, T) method


Inserts value into builder's fixed position.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Parameter | type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Position to insert characters into. |
| value | T | Value to format and insert. |

### Return Value

This pointer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)