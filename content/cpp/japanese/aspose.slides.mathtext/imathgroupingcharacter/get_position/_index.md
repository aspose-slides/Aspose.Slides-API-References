---
title: get_Position()
second_title: Aspose.Slides for C++ API リファレンス
description: "グループ化文字の位置。デフォルト: 下"
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() メソッド

グループ化文字の位置。 デフォルト: 下

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## 備考

例:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## 参照

* 列挙型 [MathTopBotPositions](../../mathtopbotpositions/)
* クラス [IMathGroupingCharacter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)