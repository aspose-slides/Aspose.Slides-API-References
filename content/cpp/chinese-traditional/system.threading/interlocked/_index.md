---
title: Interlocked
second_title: Aspose.Slides C++ API 參考手冊
description: 提供執行執行緒安全操作的 API。這是一個沒有實例服務的靜態類型。絕不可以任何方式建立其實例。
type: docs
weight: 131
url: /zh-hant/system.threading/interlocked/
---
## Interlocked 類別

提供執行執行緒安全操作的 API。這是一個沒有實例服務的靜態類型。決不應以任何方式建立其實例。

```cpp
class Interlocked
```

## 方法

| Method | Description |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | 原子地遞增值。 |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | 原子地遞增值。 |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | 比較並交換變數的值：檢查變數是否等於特定值，僅在儲存的值符合預期時才寫入新值。 |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | 比較並交換變數的值：檢查變數是否等於特定值，僅在儲存的值符合預期時才寫入新值。未實作。 |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | 比較並交換變數的值：檢查變數是否等於特定值，僅在儲存的值符合預期時才寫入新值。 |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | 原子地遞減值。 |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | 原子地遞減值。 |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | 交換變數的值：存入新值，並返回存入前的舊值。 |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | 交換變數的值：存入新值，並返回存入前的舊值。未實作。 |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | 透過 exchange-add 程序原子地遞增值。 |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | 透過 exchange-add 程序原子地遞增值。 |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | 原子地遞增值。 |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | 原子地遞增值。 |
| static **int64_t** [Read](./read/)(**int64_t**\&) | 返回作為原子操作載入的 64 位元值。 |
## 另見

* 命名空間 [System::Threading](../)
* 函式庫 [Aspose.Slides](../../)