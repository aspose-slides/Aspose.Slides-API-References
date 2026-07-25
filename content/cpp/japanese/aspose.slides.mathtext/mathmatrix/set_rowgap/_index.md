---
title: set_RowGap()
second_title: Aspose.Slides for C++ API リファレンス
description: "行列の行間の垂直間隔の値です。RowGapRule が 3 (\"Exactly\") に設定されている場合、単位は twips (ポイントの 1/20) と解釈されます。RowGapRule が 4 (\"Multiple\") に設定されている場合、単位はハーフラインとして解釈されます。デフォルト: 0"
type: docs
weight: 196
url: /ja/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) メソッド

行列の行間の垂直間隔の値です。RowGapRule が 3 (\"Exactly\") に設定されている場合、単位は twips (ポイントの 1/20) と解釈されます。RowGapRule が 4 (\"Multiple\") に設定されている場合、単位はハーフラインとして解釈されます。デフォルト: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## 備考

例:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## 参照

* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)