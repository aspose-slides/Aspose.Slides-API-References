---
title: get_RowGapRule()
second_title: Aspose.Slides for C++ API リファレンス
description: "行列の行間の垂直間隔のタイプです; 垂直間隔の単位は行またはポイント（twipとして保存）です。デフォルト: SingleSpacingGap (0)"
type: docs
weight: 157
url: /ja/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() メソッド

行列の行間の垂直間隔のタイプです; 垂直間隔の単位は行またはポイント（twipとして保存）です。デフォルト: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## 備考

例:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 参照

* 列挙型 [MathSpacingRules](../../mathspacingrules/)
* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)