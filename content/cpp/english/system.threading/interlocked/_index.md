---
title: Interlocked
second_title: Aspose.Slides for C++ API Reference
description: Provides API for thread-safe operations. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 92
url: /system.threading/interlocked/
---
## Interlocked class


Provides API for thread-safe operations. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Interlocked
```

## Methods

| Method | Description |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Increases value atomically. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Increases value atomically. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected. Not implemented. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Decrements value atomically. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Decrements value atomically. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Exchanges value on variable: stores new value and returns the value variable had immediately before storing. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Exchanges value on variable: stores new value and returns the value variable had immediately before storing. Not implemented. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Increases value atomically via exchange-add procedure. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Increases value atomically via exchange-add procedure. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Increments value atomically. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Increments value atomically. |
## See Also

* Namespace [System::Threading](../)
* Library [Aspose.Slides](../../)