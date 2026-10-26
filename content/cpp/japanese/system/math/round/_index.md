---
title: Round()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された値を最も近い整数に丸めます。
type: docs
weight: 157
url: /ja/system/math/round/
---
## Math::Round(double) メソッド

指定された値を最も近い整数に丸めます。

```cpp
static double System::Math::Round(double a)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | **double** | 丸める値 |

### 戻り値

**a** を最も近い整数に丸めた

## Math::Round(double, int) メソッド

指定された値を指定された小数桁数で最も近い値に丸めます。

```cpp
static double System::Math::Round(double value, int digits)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **double** | 丸める値 |
| digits | int | 丸められた値の小数桁数 |

### 戻り値

指定された桁数で **value** に最も近い数

## Math::Round(double, MidpointRounding) メソッド

指定された値を最も近い整数に丸めます。パラメータは、指定された値が2つの最も近い数と同じ距離にある場合の動作を指定します。

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **double** | 丸める値 |
| mode | [MidpointRounding](../../midpointrounding/) | **value** が2つの最も近い数と同じ距離にある場合の丸め処理方法を指定します。 |

### 戻り値

**value** を最も近い整数に丸めた

## Math::Round(double, int, MidpointRounding) メソッド

指定された値を指定された小数桁数で最も近い値に丸めます。パラメータは、指定された値が2つの最も近い数と同じ距離にある場合の動作を指定します。

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **double** | 丸める値 |
| digits | int | 丸められた値の小数桁数 |
| mode | [MidpointRounding](../../midpointrounding/) | **value** が2つの最も近い数と同じ距離にある場合の丸め処理方法を指定します。 |

### 戻り値

指定された桁数で **value** に最も近い数

## Math::Round(const Decimal\&) メソッド

指定された値を最も近い整数に丸めます。

```cpp
static Decimal System::Math::Round(const Decimal &d)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | 丸める値 |

### 戻り値

**d** を最も近い整数に丸めた

## Math::Round(const Decimal\&, int) メソッド

指定された値を指定された小数桁数で最も近い値に丸めます。

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | 丸める値 |
| digits | int | 丸められた値の小数桁数 |

### 戻り値

指定された桁数で **value** に最も近い数

## Math::Round(const Decimal\&, MidpointRounding) メソッド

指定された値を最も近い整数に丸めます。パラメータは、指定された値が2つの最も近い数と同じ距離にある場合の動作を指定します。

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | 丸める値 |
| mode | [MidpointRounding](../../midpointrounding/) | **value** が2つの最も近い数と同じ距離にある場合の丸め処理方法を指定します。 |

### 戻り値

**d** を最も近い整数に丸めた

## Math::Round(const Decimal\&, int, MidpointRounding) メソッド

指定された値を指定された小数桁数で最も近い値に丸めます。パラメータは、指定された値が2つの最も近い数と同じ距離にある場合の動作を指定します。

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | 丸める値 |
| digits | int | 丸められた値の小数桁数 |
| mode | [MidpointRounding](../../midpointrounding/) | **value** が2つの最も近い数と同じ距離にある場合の丸め処理方法を指定します。 |

### 戻り値

指定された桁数で **value** に最も近い数

## 参照

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../../decimal/)
* Struct [Math](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)