---
title: get_Position()
second_title: Aspose.Slides for C++ API 參考
description: "條線的位置。預設：Top"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() method


條線的位置。預設：Top

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## 備註


範例： 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## 另請參閱

* 列舉 [MathTopBotPositions](../../mathtopbotpositions/)
* 類別 [IMathBar](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)