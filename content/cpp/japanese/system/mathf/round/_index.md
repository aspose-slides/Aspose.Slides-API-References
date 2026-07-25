---
title: Round()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された値を最も近い整数値に丸めます。
type: docs
weight: 157
url: /ja/system/mathf/round/
---
## MathF::Round(float) メソッド

指定された値を最も近い整数値に丸めます。

```cpp
static float System::MathF::Round(float a)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | **float** | 丸める対象の値 |

### 戻り値

**a** を最も近い整数値に丸めたもの

## MathF::Round(float, int) メソッド

指定された値を、指定された小数桁数の最も近い値に丸めます。

```cpp
static float System::MathF::Round(float value, int digits)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **float** | 丸める対象の値 |
| digits | int | 丸めた値の小数桁数 |

### 戻り値

**value** に最も近い、指定された桁数の数

## MathF::Round(float, MidpointRounding) メソッド

指定された値を最も近い整数に丸めます。指定された値が2つの最も近い数に同等に近い場合の関数の動作を指定するパラメータがあります。

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **float** | 丸める対象の値 |
| mode | [MidpointRounding](../../midpointrounding/) | **value** が2つの最も近い数に同等に近い場合の丸め方法を指定します。 |

### 戻り値

**value** を最も近い整数に丸めたもの

## MathF::Round(float, int, MidpointRounding) メソッド

指定された値を、指定された小数桁数の最も近い値に丸めます。指定された値が2つの最も近い数に同等に近い場合の関数の動作を指定するパラメータがあります。

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **float** | 丸める対象の値 |
| digits | int | 丸めた値の小数桁数 |
| mode | [MidpointRounding](../../midpointrounding/) | **value** が2つの最も近い数に同等に近い場合の丸め方法を指定します。 |

### 戻り値

**value** に最も近い、指定された桁数の数

## 参照

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)