---
title: MathF
second_title: Aspose.Slides for C++ API 參考
description: 包含單精度浮點數值的數學函式。這是一個沒有實例服務的靜態類型。絕不應以任何方式建立其實例。
type: docs
weight: 1795
url: /zh-hant/system/mathf/
---
## MathF 結構


包含單精度浮點數值的數學函式。這是一個沒有實例服務的靜態類型。絕不應以任何方式建立其實例。

```cpp
class MathF
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static T [Abs](./abs/)(T) | 傳回指定值的絕對值。 |
| static **float** [Acos](./acos/)(**float**) | 計算指定值的反餘弦。 |
| static **float** [Asin](./asin/)(**float**) | 計算指定值的反正弦。 |
| static **float** [Atan](./atan/)(**float**) | 計算指定值的反正切。 |
| static **float** [Atan2](./atan2/)(**float**, **float**) | 計算比值的反正切。 |
| static **float** [Ceiling](./ceiling/)(**float**) | 傳回大於或等於指定值的最小整數值。 |
| static **float** [Cos](./cos/)(**float**) | 計算指定值的餘弦。 |
| static **float** [Cosh](./cosh/)(**float**) | 計算指定值的雙曲餘弦。 |
| static **float** [Exp](./exp/)(**float**) | 傳回 e 常數的指定次方。 |
| static **float** [Floor](./floor/)(**float**) | 傳回小於或等於指定值的最大整數值。 |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | 傳回指定數字除以另一指定數字的餘數。 |
| static **float** [Log](./log/)(**float**) | 傳回指定值的自然對數。 |
| static **float** [Log](./log/)(**float**, **float**) | 傳回以指定底數計算的指定值的對數。 |
| static **float** [Log10](./log10/)(**float**) | 傳回指定值的以 10 為底的對數。 |
| static **float** [Pow](./pow/)(**float**, **float**) | 傳回指定值的指定次方。 |
| static **float** [Round](./round/)(**float**) | 將指定值四捨五入為最近的整數值。 |
| static **float** [Round](./round/)(**float**, int) | 將指定值四捨五入為具有指定小數位數的最近值。 |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | 将指定值四捨五入為最近的整數。參數指定當指定值同等接近兩個最近數時函式的行為。 |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | 將指定值四捨五入為具有指定小數位數的最近值。參數指定當指定值同等接近兩個最近數時函式的行為。 |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | 將指定值四捨五入為具有指定小數位數的最近值。參數指定當指定值同等接近兩個最近數時函式的行為。 |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | 判定指定有號整數值的正負號。 |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | 判定指定浮點值的正負號。 |
| static **float** [Sin](./sin/)(**float**) | 計算指定值的正弦。 |
| static **float** [Sinh](./sinh/)(**float**) | 計算指定值的雙曲正弦。 |
| static **float** [Sqrt](./sqrt/)(**float**) | 傳回指定值的平方根。 |
| static **float** [Tan](./tan/)(**float**) | 計算指定值的正切。 |
| static **float** [Tanh](./tanh/)(**float**) | 計算指定值的雙曲正切。 |
| static **float** [Truncate](./truncate/)(**float**) | 傳回一個浮點值，其整數部份等於指定值，且所有小數位皆已捨棄。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [E](./e/) | 自然對數的底數。 |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | π 常數。 |
| static [Tau](./tau/) | Tau 值。 |

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)