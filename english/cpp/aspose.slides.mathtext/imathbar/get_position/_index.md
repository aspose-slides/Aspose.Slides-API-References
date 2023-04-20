---
title: get_Position()
second_title: Aspose.Slides for C++ API Reference
description: "Position of the bar line. Default: Top"
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() method


Position of the bar line. Default: Top

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## Remarks


Example: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## See Also

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Class [IMathBar](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)