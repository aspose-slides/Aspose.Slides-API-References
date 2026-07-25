---
title: Decimal()
second_title: Aspose.Slides for C++ API リファレンス
description: 0 を表すインスタンスを作成します。
type: docs
weight: 1
url: /ja/system/decimal/decimal/
---
## Decimal::Decimal() コンストラクタ

0 を表すインスタンスを作成します。

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) コンストラクタ

指定された値を表すインスタンスを作成します。

```cpp
System::Decimal::Decimal(std::int8_t i)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::int8_t | 構築される [Decimal](../) オブジェクトが表す 8 ビット整数値 |

## Decimal::Decimal(std::int16_t) コンストラクタ

指定された値を表すインスタンスを作成します。

```cpp
System::Decimal::Decimal(std::int16_t i)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::int16_t | 構築される [Decimal](../) オブジェクトが表す 16 ビット整数値 |

## Decimal::Decimal(std::int32_t) コンストラクタ

指定された値を表すインスタンスを作成します。

```cpp
System::Decimal::Decimal(std::int32_t i)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::int32_t | 構築される [Decimal](../) オブジェクトが表す 32 ビット整数値 |

## Decimal::Decimal(std::int64_t) コンストラクタ

指定された値を表すインスタンスを作成します。

```cpp
System::Decimal::Decimal(std::int64_t i)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::int64_t | 構築される [Decimal](../) オブジェクトが表す 64 ビット整数値 |

## Decimal::Decimal(std::uint8_t) コンストラクタ

指定された値を表すインスタンスを作成します。

```cpp
System::Decimal::Decimal(std::uint8_t i)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::uint8_t | 構築される [Decimal](../) オブジェクトが表す符号なし 8 ビット整数値 |

## Decimal::Decimal(std::uint16_t) コンストラクタ

指定された値を表すインスタンスを作成します。

```cpp
System::Decimal::Decimal(std::uint16_t i)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::uint16_t | 構築される [Decimal](../) オブジェクトが表す符号なし 16 ビット整数値 |

## Decimal::Decimal(std::uint32_t) コンストラクタ

指定された値を表すインスタンスを作成します。

```cpp
System::Decimal::Decimal(std::uint32_t i)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::uint32_t | 構築される [Decimal](../) オブジェクトが表す符号なし 32 ビット整数値 |

## Decimal::Decimal(std::uint64_t) コンストラクタ

指定された値を表すインスタンスを作成します。

```cpp
System::Decimal::Decimal(std::uint64_t i)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::uint64_t | 構築される [Decimal](../) オブジェクトが表す符号なし 64 ビット整数値 |

## Decimal::Decimal(float) コンストラクタ

指定された値を表すインスタンスを作成します。

```cpp
System::Decimal::Decimal(float f)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| f | **float** | 構築される [Decimal](../) オブジェクトが表す単精度浮動小数点値 |

## Decimal::Decimal(double) コンストラクタ

指定された値を表すインスタンスを作成します。

```cpp
System::Decimal::Decimal(double d)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| d | **double** | 構築される [Decimal](../) オブジェクトが表す倍精度浮動小数点値 |

## Decimal::Decimal(const std::string\&) コンストラクタ

std::string クラスのインスタンスとして指定された文字列表現を持つ値を表すインスタンスを作成します。

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) コンストラクタ

指定された構成要素から [Decimal](../) オブジェクトを作成します。

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lo | **int32_t** | 値の下位 32 ビット |
| mid | **int32_t** | 値の中位 32 ビット |
| hi | **int32_t** | 値の上位 32 ビット |
| isNegative | **bool** | 値が負であるかどうかを指定します |
| scale | **uint8_t** | 0 から 28 までの 10 の累乗 |

## Decimal::Decimal(const Decimal\&) コンストラクタ

指定された [Decimal](../) オブジェクトと同じ数値を表す [Decimal](../) クラスのインスタンスを作成します。

```cpp
System::Decimal::Decimal(const Decimal &d)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | 値をコピーする [Decimal](../) オブジェクト |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) コンストラクタ

2 進表現を含む整数配列から [Decimal](../) クラスのインスタンスを作成します。

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | 2 進表現を含む整数配列 |

## Decimal::Decimal(std::nullptr_t) コンストラクタ

常に ArgumentNullException をスローします。

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) コンストラクタ

指定された値を表す [Decimal](../) クラスのインスタンスを作成します。

```cpp
System::Decimal::Decimal(const number_type &value)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | 構築されるオブジェクトが表す値への定数参照 |

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)