---
title: set_RowSpacing()
second_title: Aspose.Slides for C++ API リファレンス
description: "配列の行間の間隔です。RowSpacingRule が 3 に設定されている場合にのみ使用されます。その場合、測定単位はポイントです。また、Multiple が設定されている場合は測定単位が半行になります。デフォルト: 0"
type: docs
weight: 131
url: /ja/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) メソッド


配列の行間の間隔です。RowSpacingRule が 3 に設定されている場合にのみ使用されます。その場合、測定単位はポイントです。また、Multiple が設定されている場合は測定単位が半行になります。デフォルト: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## 備考


例: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## 参照

* クラス [MathArray](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)