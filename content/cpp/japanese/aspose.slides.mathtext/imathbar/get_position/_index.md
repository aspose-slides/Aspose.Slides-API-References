---
title: get_Position()
second_title: Aspose.Slides for C++ API リファレンス
description: "バーラインの位置。デフォルト: 上"
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() メソッド

バーラインの位置。デフォルト: 上

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## 備考

例:
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## 参照

* 列挙型 [MathTopBotPositions](../../mathtopbotpositions/)
* クラス [IMathBar](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)