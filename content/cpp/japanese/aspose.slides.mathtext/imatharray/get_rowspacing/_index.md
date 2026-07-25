---
title: get_RowSpacing()
second_title: Aspose.Slides for C++ API リファレンス
description: "配列の行間の間隔です。RowSpacingRule が 3 に設定されている場合にのみ使用されます。その場合、測定単位はポイントです。また、Multiple に設定されている場合は測定単位は半行です。デフォルト: 0"
type: docs
weight: 118
url: /ja/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() メソッド

配列の行間の間隔です。RowSpacingRule が 3 に設定されている場合にのみ使用されます。その場合、測定単位はポイントです。また、Multiple に設定されている場合は測定単位は半行です。デフォルト: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## 備考

例:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## 関連項目

* クラス [IMathArray](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)