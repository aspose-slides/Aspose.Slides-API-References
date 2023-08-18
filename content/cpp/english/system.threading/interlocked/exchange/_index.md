---
title: Exchange()
second_title: Aspose.Slides for C++ API Reference
description: "Exchanges value on variable: stores new value and returns the value variable had immediately before storing."
type: docs
weight: 53
url: /system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) method


Exchanges value on variable: stores new value and returns the value variable had immediately before storing.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
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

### Return Value

Value of variable right before it was changed.

## Interlocked::Exchange(T\&, T) method


Exchanges value on variable: stores new value and returns the value variable had immediately before storing. Not implemented.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
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

### Return Value

Value of variable right before it was changed.

## See Also

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)