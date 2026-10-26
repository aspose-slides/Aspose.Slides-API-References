---
title: set_VerticalJustification()
second_title: Aspose.Slides för C++ API-referens
description: "Vertikal justering av grupptecken. Anger objektets placering i förhållande till baslinjen. Till exempel, när grupptecknet är ovanför objektet, betyder VerticalJustification av Top att objektets topp hamnar på baslinjen; när VerticalJustification är inställd på Bottom, ligger objektets botten på baslinjen Standard: Bottom för Position=Top, och Top för Position=Bottom"
type: docs
weight: 79
url: /sv/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) metod

Vertikal justering av grupptecken. Anger justeringen av objektet i förhållande till baslinjen. Till exempel, när grupptecknet är ovanför objektet, betyder VerticalJustification av Top att objektets topp ligger på baslinjen; när VerticalJustification är satt till Bottom, ligger objektets botten på baslinjen Standard: Bottom för Position=Top, och Top för Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## Anmärkningar

Exempel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Se även

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Klass [MathGroupingCharacter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)