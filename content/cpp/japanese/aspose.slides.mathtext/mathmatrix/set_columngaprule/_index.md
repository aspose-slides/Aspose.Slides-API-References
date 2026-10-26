---
title: set_ColumnGapRule()
second_title: Aspose.Slides for C++ APIリファレンス
description: "行列の列間の水平間隔のタイプです; 水平間隔の単位は em またはポイント (twips として保存) です。デフォルト: SingleSpacingGap (0)"
type: docs
weight: 118
url: /ja/aspose.slides.mathtext/mathmatrix/set_columngaprule/
---
## MathMatrix::set_ColumnGapRule(MathSpacingRules) メソッド

行列の列間の水平間隔のタイプです; 水平間隔の単位は em やポイント (twips として格納) です。デフォルト: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGapRule(MathSpacingRules value) override
```

## 備考

例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 参照

* 列挙 [MathSpacingRules](../../mathspacingrules/)
* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)