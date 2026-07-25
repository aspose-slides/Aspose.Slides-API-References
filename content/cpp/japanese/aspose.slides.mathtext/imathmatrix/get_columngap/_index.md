---
title: get_ColumnGap()
second_title: Aspose.Slides for C++ API リファレンス
description: "マトリックスの列間の水平間隔の値です; ColumnGapRule が 3 (\"Exactly\") に設定されている場合、単位はツイプ (ポイントの 1/20) と解釈されます. ColumnGapRule が 4 (\"Multiple\") に設定されている場合、単位は 0.5 em 増分の数として解釈されます. 他の場合は無視されます. デフォルト: 0"
type: docs
weight: 131
url: /ja/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() メソッド

マトリックスの列間の水平間隔の値です。ColumnGapRule が 3 ("Exactly") に設定されている場合、単位はツイプ (ポイントの 1/20) と解釈されます。ColumnGapRule が 4 ("Multiple") に設定されている場合、単位は 0.5 em 増分の数として解釈されます。他の場合は無視されます。デフォルト: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
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