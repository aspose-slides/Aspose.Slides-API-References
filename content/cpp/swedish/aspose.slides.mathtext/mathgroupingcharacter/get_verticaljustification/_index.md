---
title: get_VerticalJustification()
second_title: Aspose.Slides för C++ API-referens
description: "Vertikal justering av grupptecken. Anger objektets justering i förhållande till baslinjen. Till exempel, när grupptecknet är ovanför objektet betyder VerticalJustification med Top att objektets topp ligger på baslinjen; när VerticalJustification är inställd på Bottom ligger objektets botten på baslinjen. Standard: Bottom för Position=Top, och Top för Position=Bottom"
type: docs
weight: 66
url: /sv/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() metod


Vertikal justering av grupptecken. Anger objektets justering i förhållande till baslinjen. Till exempel, när grupptecknet är ovanför objektet betyder VerticalJustification med Top att objektets topp ligger på baslinjen; när VerticalJustification är inställd på Bottom ligger objektets botten på baslinjen. Standard: Bottom för Position=Top, och Top för Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
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