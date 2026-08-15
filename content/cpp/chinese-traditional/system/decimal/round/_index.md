---
title: Round()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的值四捨五入至最接近的整數。參數指定當指定的值與最近的兩個數字等距時函式的行為。
type: docs
weight: 404
url: /zh-hant/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) 方法


將指定的值四捨五入至最接近的整數。參數指定當指定的值與兩個最近的數字等距時函式的行為。

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | 要捨入的值 |
| mode | [MidpointRounding](../../midpointrounding/) | 指定當 **value** 與最近的兩個數字等距時如何執行捨入。 |

### 返回值

**d** 四捨五入至最接近的整數值

## Decimal::Round(const Decimal\&, int, MidpointRounding) 方法


將指定的值四捨五入至具有指定小數位數的最接近值。參數指定當指定的值與兩個最近的數字等距時函式的行為。

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | 要捨入的值 |
| digits | int | 四捨五入值的小數位數 |
| mode | [MidpointRounding](../../midpointrounding/) | 指定當 **value** 與最近的兩個數字等距時如何執行捨入。 |

### 返回值

具有指定小數位數且最接近 **value** 的數字

## 另請參閱

* Enum [MidpointRounding](../../midpointrounding/)
* 類別 [Decimal](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)