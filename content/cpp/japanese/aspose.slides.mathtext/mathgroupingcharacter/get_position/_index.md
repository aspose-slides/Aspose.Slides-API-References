---
title: get_Position()
second_title: Aspose.Slides for C++ API リファレンス
description: "グルーピング文字の位置。デフォルト: Bottom"
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/mathgroupingcharacter/get_position/
---
## MathGroupingCharacter::get_Position() メソッド


グルーピング文字の位置。デフォルト: Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_Position() override
```

## 備考


例: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## 参照

* 列挙型 [MathTopBotPositions](../../mathtopbotpositions/)
* クラス [MathGroupingCharacter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)