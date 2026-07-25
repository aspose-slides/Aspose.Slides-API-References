---
title: set_ColumnGap()
second_title: Aspose.Slides for C++ API リファレンス
description: "行列の列間の水平間隔の値です。ColumnGapRule が 3 (\"Exactly\") に設定されている場合、単位は twips (1/20 ポイント) と解釈されます。ColumnGapRule が 4 (\"Multiple\") に設定されている場合、単位は 0.5 em 増分の数として解釈されます。それ以外の場合は無視されます。既定値: 0"
type: docs
weight: 144
url: /ja/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) メソッド


行列の列間の水平間隔の値です。ColumnGapRule が 3 ("Exactly") に設定されている場合、単位は twips (1/20 ポイント) と解釈されます。ColumnGapRule が 4 ("Multiple") に設定されている場合、単位は 0.5 em 増分の数として解釈されます。それ以外の場合は無視されます。既定値: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```
## 備考


例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## 参照

* クラス [IMathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)