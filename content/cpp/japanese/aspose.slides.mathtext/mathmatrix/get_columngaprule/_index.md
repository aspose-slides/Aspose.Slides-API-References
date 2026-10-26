---
title: get_ColumnGapRule()
second_title: Aspose.Slides for C++ API リファレンス
description: "マトリックスの列間の水平間隔のタイプです; 水平間隔の単位は em またはポイント (twips として保存) です。 デフォルト: SingleSpacingGap (0)"
type: docs
weight: 105
url: /ja/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() メソッド


マトリックスの列間の水平間隔のタイプ; 水平間隔の単位は em またはポイント (twips として格納) です。 デフォルト: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## 備考


例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 参照

* 列挙体 [MathSpacingRules](../../mathspacingrules/)
* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)