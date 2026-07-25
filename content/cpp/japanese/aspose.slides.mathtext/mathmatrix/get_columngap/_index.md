---
title: get_ColumnGap()
second_title: Aspose.Slides for C++ API リファレンス
description: "行列の列間の水平間隔の値です。ColumnGapRule が 3 (\"Exactly\") に設定されている場合、単位は twips (ポイントの 1/20) と解釈されます。ColumnGapRule が 4 (\"Multiple\") に設定されている場合、単位は 0.5 em 増分の数として解釈されます。他の場合は無視されます。デフォルト: 0"
type: docs
weight: 131
url: /ja/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() メソッド


行列の列間の水平間隔の値です。ColumnGapRule が 3 (\"Exactly\") に設定されている場合、単位は twips (ポイントの 1/20) と解釈されます。ColumnGapRule が 4 (\"Multiple\") に設定されている場合、単位は 0.5 em 増分の数として解釈されます。他の場合は無視されます。デフォルト: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## 備考


例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## 関連項目

* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)