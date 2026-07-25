---
title: set_Position()
second_title: "Aspose.Slides for C++ APIリファレンス"
description: "グルーピング文字の位置。デフォルト: Bottom"
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/imathgroupingcharacter/set_position/
---
## IMathGroupingCharacter::set_Position(MathTopBotPositions) メソッド

グルーピング文字の位置。デフォルト: Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Position(MathTopBotPositions value)=0
```

## 備考

例:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## 参照

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Class [IMathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)