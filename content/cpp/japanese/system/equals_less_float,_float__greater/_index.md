---
title: Equals< float, float >()
second_title: Aspose.Slides for C++ API リファレンス
description: "単精度浮動小数点値の特殊化です。IEC 60559:1989 では、2つの浮動小数点 NaN は常に等しくないと定義されていますが、System.Object.Equals の契約により、オーバーライドは等価演算子の要件を満たす必要があります。そのため、System.Double.Equals と System.Single.Equals は 2つの NaN を比較する際に True を返し、等価演算子はその場合に False を返します（標準で要求されている通り）。"
type: docs
weight: 2705
url: /ja/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) function

単精度浮動小数点値の特殊化です。IEC 60559:1989 では、2つの浮動小数点 NaN は常に等しくないと定義されていますが、[System.Object.Equals](../object/equals/) の契約により、オーバーライドは等価演算子の要件を満たす必要があります。したがって、System.Double.Equals と System.Single.Equals は 2つの NaN を比較する際に True を返し、等価演算子はその場合に False を返します（標準で要求されている通り）。

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | const **float**\& | 最初の比較対象 |
| b | const **float**\& | 2番目の比較対象 |

### 戻り値

両方の値が NaN であるか等しい場合は True、そうでなければ false

## 関連項目

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)