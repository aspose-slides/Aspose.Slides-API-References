---
title: get_Position()
second_title: Aspose.Slides för C++ API-referens
description: "Position för grupperingstecken. Standard: Botten"
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() metod


Position för grupperingstecken. Standard: Botten

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## Anmärkningar


Exempel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Se även

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Klass [IMathGroupingCharacter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)