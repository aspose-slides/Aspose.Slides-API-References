---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API Reference
description: Substring backward lookup.
type: docs
weight: 612
url: /system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const method


Substring backward lookup.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Substring to look for. |
| startIndex | int | Position in source string to start lookup through. |

### Return Value

Index of last found substring or -1 if not found. For empty lookup string, always returns string length.

## String::LastIndexOf(const String\&, System::StringComparison) const method


Substring backward lookup.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Substring to look for. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Return Value

Index of last found substring or -1 if not found. For empty lookup string, always returns string length.

## String::LastIndexOf(const String\&, int, System::StringComparison) const method


Substring backward lookup.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Substring to look for. |
| startIndex | int | Position in source string to start lookup through. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Return Value

Index of last found substring or -1 if not found. For empty lookup string, always returns string length.

## String::LastIndexOf(const String\&, int, int, StringComparison) const method


Substring backward lookup.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Substring to look for. |
| startIndex | int | Position in source string to start lookup through. |
| count | int | Number of characters to look through. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Return Value

Index of last found substring or -1 if not found. For empty lookup string, always returns startIndex+count.

## String::LastIndexOf(char_t) const method


Character backward lookup.

```cpp
int System::String::LastIndexOf(char_t value) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | Character to look for. |

### Return Value

Index of last character position or -1 if not found.

## String::LastIndexOf(char_t, int32_t) const method


Character backward lookup.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | Character to look for. |
| startIndex | **int32_t** | Index to start lookup at. |

### Return Value

Index of last character position since startIndex or -1 if not found.

## String::LastIndexOf(char_t, int32_t, int32_t) const method


Character backward lookup.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | Character to look for. |
| startIndex | **int32_t** | Index to start lookup at. |
| count | **int32_t** | Number of characters to look through |

### Return Value

Index of last character position since startIndex or -1 if not found.

## See Also

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)