---
title: get_Position()
second_title: Aspose.Slides för C++ API-referens
description: "Position för stapellinjen. Standard: Överst"
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() metod


Position för stapellinjen. Standard: Överst

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## Anmärkningar


Exempel: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Se även

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Klass [IMathBar](../)
* Namnutrymme [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)