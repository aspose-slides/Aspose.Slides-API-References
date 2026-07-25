---
title: get_RowGap()
second_title: Aspose.Slides for C++ API リファレンス
description: "行列の行間の垂直間隔の値です。RowGapRule が 3 (\"Exactly\") に設定されている場合、単位はツイプ (ポイントの 1/20) と解釈されます。RowGapRule が 4 (\"Multiple\") に設定されている場合、単位は半行として解釈されます。デフォルト: 0"
type: docs
weight: 183
url: /ja/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() メソッド

行列の行間の垂直間隔の値です。RowGapRule が 3 ("Exactly") に設定されている場合、単位はツイプ (ポイントの 1/20) と解釈されます。RowGapRule が 4 ("Multiple") に設定されている場合、単位は半行として解釈されます。デフォルト: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
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