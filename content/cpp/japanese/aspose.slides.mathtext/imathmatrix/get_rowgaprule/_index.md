---
title: get_RowGapRule()
second_title: Aspose.Slides for C++ API リファレンス
description: "マトリックスの行間の垂直間隔のタイプです; 垂直間隔の単位は行またはポイント（twipsで保存）です。デフォルト: SingleSpacingGap (0)"
type: docs
weight: 157
url: /ja/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() メソッド

マトリックスの行間の垂直間隔のタイプです。垂直間隔の単位は行またはポイント（twipsで保存）です。既定値: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## 備考

例:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 参考

* Enum [MathSpacingRules](../../mathspacingrules/)
* クラス [IMathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)