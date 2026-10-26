---
title: get_ColumnGapRule()
second_title: Aspose.Slides for C++ API リファレンス
description: "行列の列間の水平間隔のタイプです; 水平間隔の単位は ems または points (twips に保存) です。デフォルトは SingleSpacingGap (0) です。"
type: docs
weight: 105
url: /ja/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() メソッド

行列の列間の水平間隔のタイプです。水平間隔の単位は ems またはポイント (twips に保存) です。デフォルトは SingleSpacingGap (0) です。

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## 備考

例:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 参照

* 列挙体 [MathSpacingRules](../../mathspacingrules/)
* クラス [IMathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)