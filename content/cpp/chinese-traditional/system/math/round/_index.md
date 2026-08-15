---
title: Round()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的值四捨五入為最接近的整數值。
type: docs
weight: 157
url: /zh-hant/system/math/round/
---
## Math::Round(double) 方法

將指定的值四捨五入為最接近的整數值。

```cpp
static double System::Math::Round(double a)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | **double** | 要四捨五入的值 |

### 傳回值

**a** 四捨五入為最接近的整數值

## Math::Round(double, int) 方法

將指定的值四捨五入為具有指定小數位數的最接近值。

```cpp
static double System::Math::Round(double value, int digits)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **double** | 要四捨五入的值 |
| digits | int | 四捨五入值的小數位數 |

### 傳回值

具有指定位數且最接近 **value** 的數值

## Math::Round(double, MidpointRounding) 方法

將指定的值四捨五入為最接近的整數。若指定的值與兩個最接近的數字同等接近，則參數指定函式的行為。

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **double** | 要四捨五入的值 |
| mode | [MidpointRounding](../../midpointrounding/) | 若 **value** 與兩個最接近的數字同等接近，則指定四捨五入的執行方式。 |

### 傳回值

**value** 四捨五入為最接近的整數值

## Math::Round(double, int, MidpointRounding) 方法

將指定的值四捨五入為具有指定小數位數的最接近值。若指定的值同等接近兩個最接近的數字，則參數指定函式的行為。

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **double** | 要四捨五入的值 |
| digits | int | 四捨五入值的小數位數 |
| mode | [MidpointRounding](../../midpointrounding/) | 若 **value** 與兩個最接近的數字同等接近，則指定四捨五入的執行方式。 |

### 傳回值

具有指定位數且最接近 **value** 的數值

## Math::Round(const Decimal\&) 方法

將指定的值四捨五入為最接近的整數值。

```cpp
static Decimal System::Math::Round(const Decimal &d)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | 要四捨五入的值 |

### 傳回值

**d** 四捨五入為最接近的整數值

## Math::Round(const Decimal\&, int) 方法

將指定的值四捨五入為具有指定小數位數的最接近值。

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | 要四捨五入的值 |
| digits | int | 四捨五入值的小數位數 |

### 傳回值

具有指定位數且最接近 **value** 的數值

## Math::Round(const Decimal\&, MidpointRounding) 方法

將指定的值四捨五入為最接近的整數。若指定的值與兩個最接近的數字同等接近，則參數指定函式的行為。

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | 要四捨五入的值 |
| mode | [MidpointRounding](../../midpointrounding/) | 若 **value** 與兩個最接近的數字同等接近，則指定四捨五入的執行方式。 |

### 傳回值

**d** 四捨五入為最接近的整數值

## Math::Round(const Decimal\&, int, MidpointRounding) 方法

將指定的值四捨五入為具有指定小數位數的最接近值。若指定的值同等接近兩個最接近的數字，則參數指定函式的行為。

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | 要四捨五入的值 |
| digits | int | 四捨五入值的小數位數 |
| mode | [MidpointRounding](../../midpointrounding/) | 若 **value** 與兩個最接近的數字同等接近，則指定四捨五入的執行方式。 |

### 傳回值

具有指定位數且最接近 **value** 的數值

## 另請參閱

* 列舉 [MidpointRounding](../../midpointrounding/)
* 類別 [Decimal](../../decimal/)
* 結構 [Math](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)