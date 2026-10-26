---
title: set_RowSpacing()
second_title: Aspose.Slides for C++ API リファレンス
description: "配列の行間の間隔です。RowSpacingRule が 3 に設定されている場合のみ使用されます。この場合、測定単位はポイントです。Multiple が設定されている場合、測定単位はハーフラインです。デフォルト: 0"
type: docs
weight: 131
url: /ja/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) メソッド


配列の行間の間隔です。RowSpacingRule が 3 に設定されている場合のみ使用されます。この場合、測定単位はポイントです。Multiple が設定されている場合、測定単位はハーフラインです。デフォルト: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## 備考


例:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## 参照

* クラス [IMathArray](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)