---
title: Round()
second_title: Aspose.Slides C++ API 參考
description: 將指定的值四捨五入至最接近的整數值。
type: docs
weight: 157
url: /zh-hant/system/mathf/round/
---
## MathF::Round(float) 方法

將指定的值四捨五入至最接近的整數值。

```cpp
static float System::MathF::Round(float a)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | **float** | 要四捨五入的值 |

### 返回值

**a** 四捨五入至最接近的整數值

## MathF::Round(float, int) 方法

將指定的值四捨五入至具有指定小數位數的最接近值。

```cpp
static float System::MathF::Round(float value, int digits)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **float** | 要四捨五入的值 |
| digits | int | 四捨五入後的值中的小數位數 |

### 返回值

具有指定小數位數且最接近 **value** 的數字

## MathF::Round(float, MidpointRounding) 方法

將指定的值四捨五入至最接近的整數。若指定的值同時等距於兩個最近的整數，則由參數指定函式的行為。

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **float** | 要四捨五入的值 |
| mode | [MidpointRounding](../../midpointrounding/) | 指定當 **value** 同時等距於兩個最近的整數時如何進行四捨五入。 |

### 返回值

**value** 四捨五入至最接近的整數值

## MathF::Round(float, int, MidpointRounding) 方法

將指定的值四捨五入至具有指定小數位數的最接近值。若指定的值同時等距於兩個最近的整數，則由參數指定函式的行為。

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **float** | 要四捨五入的值 |
| digits | int | 四捨五入後的值中的小數位數 |
| mode | [MidpointRounding](../../midpointrounding/) | 指定當 **value** 同時等距於兩個最近的整數時如何進行四捨五入。 |

### 返回值

具有指定小數位數且最接近 **value** 的數字

## 另請參閱

* 列舉 [MidpointRounding](../../midpointrounding/)
* 結構 [MathF](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)