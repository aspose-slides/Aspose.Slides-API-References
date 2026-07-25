---
title: Math
second_title: Aspose.Slides for C++ API リファレンス
description: 数学関数を含みます。これはインスタンスサービスを持たない静的型です。いかなる方法でもインスタンスを作成してはなりません。
type: docs
weight: 1782
url: /ja/system/math/
---
## Math 構造体

数学関数を含みます。これはインスタンスサービスを持たない静的型です。いかなる方法でもインスタンスを作成してはなりません。

```cpp
class Math
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static T [Abs](./abs/)(T) | 指定された値の絶対値を返します。 |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | 指定された [Decimal](../decimal/) オブジェクトで表される値の絶対値を返します。 |
| static **double** [Acos](./acos/)(**double**) | 指定された値の逆余弦を計算します。 |
| static **double** [Asin](./asin/)(**double**) | 指定された値の逆正弦を計算します。 |
| static **double** [Atan](./atan/)(**double**) | 指定された値の逆正接を計算します。 |
| static **double** [Atan2](./atan2/)(**double**, **double**) | 指定された値の比の逆正接を計算します。 |
| static **int64_t** [BigMul](./bigmul/)(int, int) | 2つの32ビット整数の完全な積を返します。 |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | 指定された値以上の最小の整数値を返します。 |
| static **double** [Ceiling](./ceiling/)(**double**) | 指定された値以上の最小の整数値を返します。 |
| static **double** [Cos](./cos/)(**double**) | 指定された値の余弦を計算します。 |
| static **double** [Cosh](./cosh/)(**double**) | 指定された値の双曲線余弦を計算します。 |
| static int [DivRem](./divrem/)(int, int, int\&) | 2つの32ビット整数の商と余りを計算します。 |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | 2つの64ビット整数の商と余りを計算します。 |
| static **double** [Exp](./exp/)(**double**) | 指定された指数で e 定数をべき乗した結果を返します。 |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | 指定された値以下の最大の整数値を返します。 |
| static **double** [Floor](./floor/)(**double**) | 指定された値以下の最大の整数値を返します。 |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | 指定された数を別の指定された数で除算した際の余りを返します。 |
| static **double** [Log](./log/)(**double**) | 指定された値の自然対数を返します。 |
| static **double** [Log](./log/)(**double**, **double**) | 指定された基数で指定された値の対数を返します。 |
| static **double** [Log10](./log10/)(**double**) | 指定された値の常用対数（底10）を返します。 |
| static auto [Max](./max/)(T0, T1) | 指定された2つの数値のうち最大の値を返します。 |
| static T0 [Max](./max/)(T0, T1) | 指定された2つの数値のうち最大の値を返します。 |
| **float** [Max_](./max_/)(**float**, **float**) | 指定された2つの単精度浮動小数点数のうち最大の値を返します。 |
| **double** [Max_](./max_/)(**double**, **double**) | 指定された2つの倍精度浮動小数点数のうち最大の値を返します。 |
| static auto [Min](./min/)(T0, T1) | 指定された2つの数値のうち最小の値を返します。 |
| static T0 [Min](./min/)(T0, T1) | 指定された2つの数値のうち最小の値を返します。 |
| **float** [Min_](./min_/)(**float**, **float**) | 指定された2つの単精度浮動小数点数のうち最小の値を返します。 |
| **double** [Min_](./min_/)(**double**, **double**) | 指定された2つの倍精度浮動小数点数のうち最小の値を返します。 |
| static T [Modulus](./modulus/)(T, T) | ある指定された値を別の指定された値で除算した際の余りを計算します。 |
| static **double** [Pow](./pow/)(**double**, **double**) | 指定された値を指定された指数でべき乗した結果を返します。 |
| static **double** [Round](./round/)(**double**) | 指定された値を最も近い整数に丸めます。 |
| static **double** [Round](./round/)(**double**, int) | 指定された小数桁数で、指定された値を最も近い値に丸めます。 |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | 指定された値を最も近い整数に丸めます。パラメータは、指定された値が2つの最も近い数と同じ距離にある場合の関数の動作を指定します。 |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | 指定された値を指定された小数桁数で最も近い値に丸めます。パラメータは、指定された値が2つの最も近い数と同じ距離にある場合の関数の動作を指定します。 |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | 指定された値を最も近い整数に丸めます。 |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | 指定された値を指定された小数桁数で最も近い値に丸めます。 |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | 指定された値を最も近い整数に丸めます。パラメータは、指定された値が2つの最も近い数と同じ距離にある場合の関数の動作を指定します。 |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | 指定された値を指定された小数桁数で最も近い値に丸めます。パラメータは、指定された値が2つの最も近い数と同じ距離にある場合の関数の動作を指定します。 |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | 指定された符号付き整数値の符号を判定します。 |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | 指定された浮動小数点数の符号を判定します。 |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | 指定された十進数値の符号を判定します。 |
| static **double** [Sin](./sin/)(**double**) | 指定された値の正弦を計算します。 |
| static **double** [Sinh](./sinh/)(**double**) | 指定された値の双曲線正弦を計算します。 |
| static **double** [Sqrt](./sqrt/)(**double**) | 指定された値の平方根を返します。 |
| static **double** [Tan](./tan/)(**double**) | 指定された値の正接を計算します。 |
| static **double** [Tanh](./tanh/)(**double**) | 指定された値の双曲線正接を計算します。 |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | [Decimal](../decimal/) オブジェクトを返します。このオブジェクトは、指定された [Decimal](../decimal/) オブジェクトで表される値の整数部分と等しい値を表し、小数部分はすべて破棄されたものです。 |
| static **double** [Truncate](./truncate/)(**double**) | 指定された値の整数部分と等しく、小数部分がすべて破棄された倍精度浮動小数点数を返します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [E](./e/) | 自然対数の底。 |
| static [NaN](./nan/) | NaN（非数）値を表します。 |
| static [NegativeInfinity](./negativeinfinity/) | 負の無限大を表します。 |
| static [PI](./pi/) | 円周率 Pi の定数です。 |
| static [PositiveInfinity](./positiveinfinity/) | 正の無限大を表します。 |

## 備考

```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // 絶対値を出力します。
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // PI/2 の正弦と PI の余弦を出力します。
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
このコード例は次の出力を生成します:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## 参照

* Namespace [System](../)
* Library [Aspose.Slides](../../)