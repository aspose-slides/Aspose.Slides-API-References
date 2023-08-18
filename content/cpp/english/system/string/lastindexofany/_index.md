---
title: LastIndexOfAny()
second_title: Aspose.Slides for C++ API Reference
description: Looks for any of passed characters through whole string backwardly. Compares last string character to all characters in anyOf, then compares previous one and so on. Returns index of the first match found.
type: docs
weight: 625
url: /system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const method


Looks for any of passed characters through whole string backwardly. Compares last string character to all characters in anyOf, then compares previous one and so on. Returns index of the first match found.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) of characters to look for. Order doesn't matter. |

### Return Value

Index of the last matching character or -1 if not found.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Looks for any of passed characters through substring backwardly. Compares last string character to all characters in anyOf, then compares previous one and so on. Returns index of the first match found.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) of characters to look for. Order doesn't matter. |
| startindex | **int32_t** | Index to start lookup from. |

### Return Value

Index of the last matching character or -1 if not found.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Looks for any of passed characters through substring backwardly. Compares last string character to all characters in anyOf, then compares previous one and so on. Returns index of the first match found.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) of characters to look for. Order doesn't matter. |
| startindex | **int32_t** | Index to start lookup from. |
| count | **int32_t** | Number of characters to look through. |

### Return Value

Index of the last matching character or -1 if not found.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)