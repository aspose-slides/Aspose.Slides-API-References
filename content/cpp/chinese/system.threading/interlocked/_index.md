---
title: Interlocked
second_title: Aspose.Slides for C++ API 参考
description: 提供线程安全操作的 API。这是一个无实例服务的静态类型。切勿以任何方式创建其实例。
type: docs
weight: 131
url: /zh/system.threading/interlocked/
---
## Interlocked 类

提供线程安全操作的 API。这是一个无实例服务的静态类型。切勿以任何方式创建其实例。

```cpp
class Interlocked
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | 原子递增值。 |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | 原子递增值。 |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | 比较交换变量的值：检查变量是否等于特定值，仅在存储的值匹配预期时才存储新值。 |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | 比较交换变量的值：检查变量是否等于特定值，仅在存储的值匹配预期时才存储新值。未实现。 |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | 比较交换变量的值：检查变量是否等于特定值，仅在存储的值匹配预期时才存储新值。 |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | 原子递减值。 |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | 原子递减值。 |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | 交换变量的值：存储新值并返回存储前变量的原始值。 |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | 交换变量的值：存储新值并返回存储前变量的原始值。未实现。 |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | 通过 exchange-add 过程原子递增值。 |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | 通过 exchange-add 过程原子递增值。 |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | 原子递增值。 |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | 原子递增值。 |
| static **int64_t** [Read](./read/)(**int64_t**\&) | 返回一个 64 位值，作为原子操作加载。 |

## 另请参见

* 命名空间 [System::Threading](../)
* 库 [Aspose.Slides](../../)