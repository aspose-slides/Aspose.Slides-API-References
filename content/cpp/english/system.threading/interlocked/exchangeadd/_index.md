---
title: ExchangeAdd()
second_title: Aspose.Slides for C++ API Reference
description: Increases value atomically via exchange-add procedure.
type: docs
weight: 40
url: /system.threading/interlocked/exchangeadd/
---
## Interlocked::ExchangeAdd(int32_t\&, int32_t) method


Increases value atomically via exchange-add procedure.

```cpp
static int32_t System::Threading::Interlocked::ExchangeAdd(int32_t &location1, int32_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | **int32_t**\& | Variable reference to increase. |
| value | **int32_t** | Value to add to **location1**. |

### Return Value

Value of variable right after it was increased.

## Interlocked::ExchangeAdd(int64_t\&, int64_t) method


Increases value atomically via exchange-add procedure.

```cpp
static int64_t System::Threading::Interlocked::ExchangeAdd(int64_t &location1, int64_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | **int64_t**\& | Variable reference to increase. |
| value | **int64_t** | Value to add to **location1**. |

### Return Value

Value of variable right after it was increased.

## See Also

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)