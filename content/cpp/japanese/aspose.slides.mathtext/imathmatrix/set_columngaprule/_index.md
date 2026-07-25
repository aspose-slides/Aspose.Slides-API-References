---
title: set_ColumnGapRule()
second_title: Aspose.Slides for C++ API リファレンス
description: "行列の列間の水平間隔のタイプです; 水平間隔の単位は em またはポイント (twips として保存) です。デフォルト: SingleSpacingGap (0)"
type: docs
weight: 118
url: /ja/aspose.slides.mathtext/imathmatrix/set_columngaprule/
---
## IMathMatrix::set_ColumnGapRule(MathSpacingRules) メソッド

マトリックスの列間の水平間隔のタイプです。水平間隔の単位は em またはポイント (twips として保存) です。デフォルト: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGapRule(MathSpacingRules value)=0
```

## 備考

例:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 参照

* Enum [MathSpacingRules](../../mathspacingrules/)
* クラス [IMathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)