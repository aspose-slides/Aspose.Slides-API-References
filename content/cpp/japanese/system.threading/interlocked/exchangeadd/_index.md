---
title: ExchangeAdd()
second_title: Aspose.Slides for C++ API リファレンス
description: 交換加算手順により、値をアトミックに増加させます。
type: docs
weight: 53
url: /ja/system.threading/interlocked/exchangeadd/
---
## Interlocked::ExchangeAdd(int32_t\&, int32_t) メソッド


交換加算手順により、値をアトミックに増加させます。

```cpp
static int32_t System::Threading::Interlocked::ExchangeAdd(int32_t &location1, int32_t value)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | **int32_t**\& | 増加させる対象の変数参照。 |
| value | **int32_t** | **location1** に加える値。 |

### 戻り値

増加直後の変数の値。

## Interlocked::ExchangeAdd(int64_t\&, int64_t) メソッド


交換加算手順により、値をアトミックに増加させます。

```cpp
static int64_t System::Threading::Interlocked::ExchangeAdd(int64_t &location1, int64_t value)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | **int64_t**\& | 増加させる対象の変数参照。 |
| value | **int64_t** | **location1** に加える値。 |

### 戻り値

増加直後の変数の値。

## 参照

* クラス [Interlocked](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)