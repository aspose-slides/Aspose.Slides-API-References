---
title: get_Position()
second_title: Aspose.Slides の C++ API リファレンス
description: "バー線の位置。デフォルト: 上"
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/mathbar/get_position/
---
## MathBar::get_Position() メソッド


バー線の位置。デフォルト: 上

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathBar::get_Position() override
```

## 備考


例: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## 参照

* 列挙型 [MathTopBotPositions](../../mathtopbotpositions/)
* クラス [MathBar](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)