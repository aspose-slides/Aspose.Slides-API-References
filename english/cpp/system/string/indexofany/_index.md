---
title: IndexOfAny()
second_title: Aspose.Slides for C++ API Reference
description: Character forward lookup.
type: docs
weight: 599
url: /cpp/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const method


Character forward lookup.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Character to look for. |
| startIndex | int | Index to start lookup at. |

### Return Value

Index of first character position since startIndex or -1 if not found.

## String::IndexOfAny(const String\&, int) const method


Consequently looks for all characters of str in this. If first character is found, its position is returned, otherwise looks for the second one and so on.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) of characters to look for. Order of characters matters. |
| startIndex | int | Position to start lookup from. |

### Return Value

Index of first found character or -1 if none is found.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const method


Looks for any of passed characters through the whole string. Compares first string character to all characters in anyOf, then compares second one and so on. Returns index of the first one matching any of the target characters.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) of characters to look for. Order doesn't matter. |

### Return Value

Index of the first matching character or -1 if not found.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Looks for any of passed characters through substring. Compares first string character to all characters in anyOf, then compares second one and so on. Returns index of the first one matching any of the target characters.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) of characters to look for. Order doesn't matter. |
| startindex | **int32_t** | Index to start lookup from. |

### Return Value

Index of the first matching character or -1 if not found.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Looks for any of passed characters through substring. Compares first string character to all characters in anyOf, then compares second one and so on. Returns index of the first one matching any of the target characters.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) of characters to look for. Order doesn't matter. |
| startindex | **int32_t** | Index to start lookup from. |
| count | **int32_t** | Number of characters to look through. |

### Return Value

Index of the first matching character or -1 if not found.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)