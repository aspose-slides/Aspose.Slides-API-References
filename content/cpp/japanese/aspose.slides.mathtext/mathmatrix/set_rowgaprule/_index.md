---
title: set_RowGapRule()
second_title: Aspose.Slides for C++ API リファレンス
description: "行列の行間の垂直間隔のタイプです; 垂直間隔の単位は行またはポイント（twipsとして保存）。デフォルト: SingleSpacingGap (0)"
type: docs
weight: 170
url: /ja/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) メソッド


行列の行間の垂直間隔のタイプです。垂直間隔の単位は行またはポイント（twips単位で格納）です。デフォルト: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
```

## 備考


例:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 参照

* Enum [MathSpacingRules](../../mathspacingrules/)
* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)