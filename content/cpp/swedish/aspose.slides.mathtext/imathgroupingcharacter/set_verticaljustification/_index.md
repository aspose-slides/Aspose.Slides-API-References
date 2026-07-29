---
title: set_VerticalJustification()
second_title: Aspose.Slides för C++ API-referens
description: "Vertikal justering av grupptecken. Anger objektets justering i förhållande till baslinjen. Till exempel, när grupptecknet är ovanför objektet, betyder VerticalJustification av Top att objektets topp faller på baslinjen; när VerticalJustification är satt till Bottom ligger objektets botten på baslinjen Standard: Bottom för Position=Top, och Top för Position=Bottom"
type: docs
weight: 79
url: /sv/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) method

Vertikal justering av grupptecken. Anger objektets justering i förhållande till baslinjen. Till exempel, när grupptecknet är över objektet betyder VerticalJustification av Top att objektets topp faller på baslinjen; när VerticalJustification är satt till Bottom, ligger objektets botten på baslinjen Standard: Bottom för Position=Top, och Top för Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## Anmärkningar

Exempel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Se även

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Klass [IMathGroupingCharacter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)