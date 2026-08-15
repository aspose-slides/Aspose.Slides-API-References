---
title: Math
second_title: Aspose.Slides C++ API 參考文件
description: 包含數學函式。此為靜態型別，沒有實例服務。絕不應以任何方式建立其實例。
type: docs
weight: 1782
url: /zh-hant/system/math/
---
## Math 結構

包含數學函式。此為靜態型別，沒有實例服務。絕不應以任何方式建立其實例。

```cpp
class Math
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static T [Abs](./abs/)(T) | 傳回指定值的絕對值。 |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | 傳回由指定 [Decimal](../decimal/) 物件所表示的值的絕對值。 |
| static **double** [Acos](./acos/)(**double**) | 計算指定值的反餘弦。 |
| static **double** [Asin](./asin/)(**double**) | 計算指定值的反正弦。 |
| static **double** [Atan](./atan/)(**double**) | 計算指定值的反正切。 |
| static **double** [Atan2](./atan2/)(**double**, **double**) | 計算指定值之比值的反正切。 |
| static **int64_t** [BigMul](./bigmul/)(int, int) | 傳回兩個 32 位元整數的完整乘積。 |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | 傳回大於或等於指定值的最小整數值。 |
| static **double** [Ceiling](./ceiling/)(**double**) | 傳回大於或等於指定值的最小整數值。 |
| static **double** [Cos](./cos/)(**double**) | 計算指定值的餘弦。 |
| static **double** [Cosh](./cosh/)(**double**) | 計算指定值的雙曲餘弦。 |
| static int [DivRem](./divrem/)(int, int, int\&) | 計算兩個 32 位元整數的商與餘數。 |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | 計算兩個 64 位元整數的商與餘數。 |
| static **double** [Exp](./exp/)(**double**) | 傳回 e 常數的指定次方。 |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | 傳回小於或等於指定值的最大整數值。 |
| static **double** [Floor](./floor/)(**double**) | 傳回小於或等於指定值的最大整數值。 |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | 傳回指定數字除以另一指定數字的餘數。 |
| static **double** [Log](./log/)(**double**) | 傳回指定值的自然對數。 |
| static **double** [Log](./log/)(**double**, **double**) | 傳回指定底數的指定值的對數。 |
| static **double** [Log10](./log10/)(**double**) | 傳回指定值的以 10 為底的對數。 |
| static auto [Max](./max/)(T0, T1) | 傳回兩個指定數值中較大的那個。 |
| static T0 [Max](./max/)(T0, T1) | 傳回兩個指定數值中較大的那個。 |
| **float** [Max_](./max_/)(**float**, **float**) | 傳回兩個指定單精度浮點數值中較大的那個。 |
| **double** [Max_](./max_/)(**double**, **double**) | 傳回兩個指定雙精度浮點數值中較大的那個。 |
| static auto [Min](./min/)(T0, T1) | 傳回兩個指定數值中較小的那個。 |
| static T0 [Min](./min/)(T0, T1) | 傳回兩個指定數值中較小的那個。 |
| **float** [Min_](./min_/)(**float**, **float**) | 傳回兩個指定單精度浮點數值中較小的那個。 |
| **double** [Min_](./min_/)(**double**, **double**) | 傳回兩個指定雙精度浮點數值中較小的那個。 |
| static T [Modulus](./modulus/)(T, T) | 計算指定值除以另一指定值的餘數。 |
| static **double** [Pow](./pow/)(**double**, **double**) | 傳回指定值的指定次方。 |
| static **double** [Round](./round/)(**double**) | 將指定值四捨五入至最接近的整數值。 |
| static **double** [Round](./round/)(**double**, int) | 將指定值四捨五入至指定小數位數的最接近值。 |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | 將指定值四捨五入至最接近的整數。若指定值同等接近兩個最近的數字，則由參數指定函式的行為。 |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | 將指定值四捨五入至指定小數位數的最接近值。若指定值同等接近兩個最近的數字，則由參數指定函式的行為。 |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | 將指定值四捨五入至最接近的整數值。 |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | 將指定值四捨五入至指定小數位數的最接近值。 |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | 將指定值四捨五入至最接近的整數。若指定值同等接近兩個最近的數字，則由參數指定函式的行為。 |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | 將指定值四捨五近至指定小數位數的最接近值。若指定值同等接近兩個最近的數字，則由參數指定函式的行為。 |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | 判斷指定帶符號整數值的正負號。 |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | 判斷指定浮點數值的正負號。 |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | 判斷指定十進位值的正負號。 |
| static **double** [Sin](./sin/)(**double**) | 計算指定值的正弦。 |
| static **double** [Sinh](./sinh/)(**double**) | 計算指定值的雙曲正弦。 |
| static **double** [Sqrt](./sqrt/)(**double**) | 傳回指定值的平方根。 |
| static **double** [Tan](./tan/)(**double**) | 計算指定值的正切。 |
| static **double** [Tanh](./tanh/)(**double**) | 計算指定值的雙曲正切。 |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | 傳回 [Decimal](../decimal/) 物件，該物件代表其整數部分等於由指定 [Decimal](../decimal/) 物件所表示之值，且已捨棄所有小數位。 |
| static **double** [Truncate](./truncate/)(**double**) | 傳回一個雙精度浮點數值，其整數部分等於指定值，且已捨棄所有小數位。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [E](./e/) | 自然對數的底數。 |
| static [NaN](./nan/) | 代表非數值 (NaN)。 |
| static [NegativeInfinity](./negativeinfinity/) | 代表負無限大。 |
| static [PI](./pi/) | π 常數。 |
| static [PositiveInfinity](./positiveinfinity/) | 代表正無限大。 |

## 備註



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // 列印絕對值。
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // 列印 PI/2 的正弦與 PI 的餘弦。
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
此程式碼範例產生以下輸出:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## 另請參閱

* Namespace [System](../)
* Library [Aspose.Slides](../../)