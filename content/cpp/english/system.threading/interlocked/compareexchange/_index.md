---
title: CompareExchange()
second_title: Aspose.Slides for C++ API Reference
description: "Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected."
type: docs
weight: 66
url: /system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T\&, T, T) method


Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Variable type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | T\& | Variable reference to change. |
| value | T | Value to store. |
| comparand | T | Value to compare variable's value to before exchanging. |

### Return Value

Value of variable on operation start regardless whether it was changed or not.

## Interlocked::CompareExchange(T\&, T, T) method


Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected. Not implemented.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Variable type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | T\& | Variable reference to change. |
| value | T | Value to store. |
| comparand | T | Value to compare variable's value to before exchanging. |

### Return Value

Value of variable on operation start regardless whether it was changed or not.

## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) method


Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | **int32_t**\& | Variable reference to change. |
| value | **int32_t** | Value to store. |
| comparand | **int32_t** | Value to compare variable's value to before exchanging. |
| succeeded | **bool**\& | Reference to variable which is set to true if exchange took place and to false otherwise. |

### Return Value

Value of variable on operation start regardless whether it was changed or not.

## See Also

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)