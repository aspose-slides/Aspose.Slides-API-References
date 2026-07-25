---
title: get_RowGap()
second_title: Aspose.Slides for C++ API リファレンス
description: "マトリックスの行間の垂直間隔の値です; RowGapRule が 3 (\"Exactly\") に設定されている場合、単位はツイップ (1/20ポイント) と解釈されます RowGapRule が 4 (\"Multiple\") に設定されている場合、単位はハーフラインとして解釈されます. デフォルト: 0"
type: docs
weight: 183
url: /ja/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() method

マトリックスの行間の垂直間隔の値です。RowGapRule が 3 (\"Exactly\") に設定されている場合、単位はツイップ (1/20th of a point) と解釈されます。RowGapRule が 4 (\"Multiple\") に設定されている場合、単位はハーフラインとして解釈されます。デフォルト: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## 備考

例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## 関連項目

* クラス [IMathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)