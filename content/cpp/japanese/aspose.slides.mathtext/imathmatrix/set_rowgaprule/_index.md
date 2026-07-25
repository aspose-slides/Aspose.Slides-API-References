---
title: set_RowGapRule()
second_title: Aspose.Slides for C++ API リファレンス
description: "行列の行間の垂直間隔の種類です。垂直間隔の単位は行またはポイント（twips で保存）です。デフォルト: SingleSpacingGap (0)"
type: docs
weight: 170
url: /ja/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) メソッド

行列の行間の垂直間隔の種類です。垂直間隔の単位は行またはポイント（twips で保存）です。デフォルト: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
```

## 備考


例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 参照

* 列挙型 [MathSpacingRules](../../mathspacingrules/)
* クラス [IMathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)