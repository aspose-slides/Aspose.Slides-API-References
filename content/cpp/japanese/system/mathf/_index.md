---
title: MathF
second_title: Aspose.Slides for C++ API リファレンス
description: 単精度浮動小数点値用の数学関数を含みます。これはインスタンスサービスを持たない static 型です。いかなる方法でもインスタンスを作成すべきではありません。
type: docs
weight: 1795
url: /ja/system/mathf/
---
## MathF 構造体

単精度浮動小数点値用の数学関数を含みます。これはインスタンスサービスを持たない static 型です。いかなる方法でもインスタンスを作成すべきではありません。

```cpp
class MathF
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static T [Abs](./abs/)(T) | 指定された値の絶対値を返します。 |
| static **float** [Acos](./acos/)(**float**) | 指定された値の逆余弦を計算します。 |
| static **float** [Asin](./asin/)(**float**) | 指定された値の逆正弦を計算します。 |
| static **float** [Atan](./atan/)(**float**) | 指定された値の逆正接を計算します。 |
| static **float** [Atan2](./atan2/)(**float**, **float**) | 指定された値の比率の逆正接を計算します。 |
| static **float** [Ceiling](./ceiling/)(**float**) | 指定された値以上の最小の整数値を返します。 |
| static **float** [Cos](./cos/)(**float**) | 指定された値の余弦を計算します。 |
| static **float** [Cosh](./cosh/)(**float**) | 指定された値の双曲余弦を計算します。 |
| static **float** [Exp](./exp/)(**float**) | 指定された指数で e 定数をべき乗した値を返します。 |
| static **float** [Floor](./floor/)(**float**) | 指定された値以下の最大の整数値を返します。 |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | 指定された数を別の数で除算した余りを返します。 |
| static **float** [Log](./log/)(**float**) | 指定された値の自然対数を返します。 |
| static **float** [Log](./log/)(**float**, **float**) | 指定された基数での指定された値の対数を返します。 |
| static **float** [Log10](./log10/)(**float**) | 指定された値の常用対数（10 底）を返します。 |
| static **float** [Pow](./pow/)(**float**, **float**) | 指定された値を指定された指数でべき乗した結果を返します。 |
| static **float** [Round](./round/)(**float**) | 指定された値を最も近い整数に丸めます。 |
| static **float** [Round](./round/)(**float**, int) | 指定された小数点以下桁数で指定された値を丸めます。 |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | 指定された値を最も近い整数に丸めます。パラメーターは指定された値が二つの最も近い数と同距離の場合の動作を指定します。 |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | 指定された小数点以下桁数で指定された値を丸めます。パラメーターは指定された値が二つの最も近い数と同距離の場合の動作を指定します。 |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | 指定された小数点以下桁数で指定された値を丸めます。パラメーターは指定された値が二つの最も近い数と同距離の場合の動作を指定します。 |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | 指定された符号付き整数値の符号を判定します。 |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | 指定された浮動小数点値の符号を判定します。 |
| static **float** [Sin](./sin/)(**float**) | 指定された値の正弦を計算します。 |
| static **float** [Sinh](./sinh/)(**float**) | 指定された値の双曲正弦を計算します。 |
| static **float** [Sqrt](./sqrt/)(**float**) | 指定された値の平方根を返します。 |
| static **float** [Tan](./tan/)(**float**) | 指定された値の正接を計算します。 |
| static **float** [Tanh](./tanh/)(**float**) | 指定された値の双曲正接を計算します。 |
| static **float** [Truncate](./truncate/)(**float**) | 指定された値の整数部と同じで小数部をすべて破棄した float 精度の浮動小数点値を返します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [E](./e/) | 自然対数の底。 |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | 円周率 (π) 定数。 |
| static [Tau](./tau/) | タウ値。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)