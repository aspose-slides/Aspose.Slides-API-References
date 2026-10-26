---
title: set_Position()
second_title: Aspose.Slides for C++ API 參考
description: "條形線的位置。預設：Top"
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathbar/set_position/
---
## IMathBar::set_Position(MathTopBotPositions) 方法

條形線的位置。預設：Top

```cpp
virtual void Aspose::Slides::MathText::IMathBar::set_Position(MathTopBotPositions value)=0
```

## 備註

範例：
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## 另見

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* 類別 [IMathBar](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)