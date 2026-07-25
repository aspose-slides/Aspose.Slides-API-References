---
title: Round()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された値を最も近い整数に丸めます。パラメーターは、指定された値が二つの最も近い数と同等に近い場合の関数の動作を指定します。
type: docs
weight: 404
url: /ja/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) メソッド

指定された値を最も近い整数に丸めます。パラメーターは、指定された値が二つの最も近い数値と同じ距離にある場合の関数の動作を指定します。

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| d | const [Decimal](../)\& | 丸める対象の値 |
| mode | [MidpointRounding](../../midpointrounding/) | **value** が二つの最も近い数値と同じ距離にある場合の丸め方法を指定します。 |

### 戻り値

**d** を最も近い整数値に丸めた結果

## Decimal::Round(const Decimal\&, int, MidpointRounding) メソッド

指定された値を指定された小数桁数で最も近い値に丸めます。パラメーターは、指定された値が二つの最も近い数値と同じ距離にある場合の関数の動作を指定します。

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| d | const [Decimal](../)\& | 丸める対象の値 |
| digits | int | 丸めた結果の小数桁数 |
| mode | [MidpointRounding](../../midpointrounding/) | **value** が二つの最も近い数値と同じ距離にある場合の丸め方法を指定します。 |

### 戻り値

指定された桁数で **value** に最も近い数値

## 参照

* 列挙体 [MidpointRounding](../../midpointrounding/)
* クラス [Decimal](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)