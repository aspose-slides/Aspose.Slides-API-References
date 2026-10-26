---
title: Interlocked
second_title: Aspose.Slides for C++ API リファレンス
description: スレッドセーフな操作のための API を提供します。これはインスタンスサービスを持たない静的型です。いかなる方法でもインスタンスを作成してはいけません。
type: docs
weight: 131
url: /ja/system.threading/interlocked/
---
## Interlocked クラス

スレッドセーフな操作のための API を提供します。これはインスタンスサービスを持たない静的型です。いかなる方法でもインスタンスを作成してはなりません。

```cpp
class Interlocked
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | 値をアトミックに増加させます。 |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | 値をアトミックに増加させます。 |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | 変数の値を比較交換します: 変数が特定の値と等しいか確認し、期待値と一致した場合にのみ新しい値を格納します。 |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | 変数の値を比較交換します: 変数が特定の値と等しいか確認し、期待値と一致した場合にのみ新しい値を格納します。実装されていません。 |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | 変数の値を比較交換します: 変数が特定の値と等しいか確認し、期待値と一致した場合にのみ新しい値を格納します。 |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | 値をアトミックにデクリメントします。 |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | 値をアトミックにデクリメントします。 |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | 変数の値を交換します: 新しい値を格納し、格納直前の変数の値を返します。 |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | 変数の値を交換します: 新しい値を格納し、格納直前の変数の値を返します。実装されていません。 |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | 交換加算手順により値をアトミックに増加させます。 |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | 交換加算手順により値をアトミックに増加させます。 |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | 値をアトミックにインクリメントします。 |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | 値をアトミックにインクリメントします。 |
| static **int64_t** [Read](./read/)(**int64_t**\&) | 64ビットの値を返します。原子操作としてロードされます。 |

## 参照

* 名前空間 [System::Threading](../)
* ライブラリ [Aspose.Slides](../../)