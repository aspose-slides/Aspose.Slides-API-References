---
title: ExchangeAdd()
second_title: Aspose.Slides for C++ API 参考
description: 通过 exchange-add 过程原子地增加值。
type: docs
weight: 53
url: /zh/system.threading/interlocked/exchangeadd/
---
## Interlocked::ExchangeAdd(int32_t\&, int32_t) 方法


通过 exchange-add 过程原子地增加值。

```cpp
static int32_t System::Threading::Interlocked::ExchangeAdd(int32_t &location1, int32_t value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location1 | **int32_t**\& | 要增加的变量引用。 |
| value | **int32_t** | 要添加到 **location1** 的值。 |

### 返回值

变量在增加后立即的值。

## Interlocked::ExchangeAdd(int64_t\&, int64_t) 方法


通过 exchange-add 过程原子地增加值。

```cpp
static int64_t System::Threading::Interlocked::ExchangeAdd(int64_t &location1, int64_t value)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location1 | **int64_t**\& | 要增加的变量引用。 |
| value | **int64_t** | 要添加到 **location1** 的值。 |

### 返回值

变量在增加后立即的值。

## 另见

* 类 [Interlocked](../)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)