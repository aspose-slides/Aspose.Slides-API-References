---
title: set_Position()
second_title: Aspose.Slides for C++ API リファレンス
description: "グループ化文字の位置。デフォルト: Bottom"
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/mathgroupingcharacter/set_position/
---
## MathGroupingCharacter::set_Position(MathTopBotPositions) メソッド


グループ化文字の位置。既定: Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_Position(MathTopBotPositions value) override
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