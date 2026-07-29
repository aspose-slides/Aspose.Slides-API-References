---
title: get_VerticalJustification()
second_title: Aspose.Slides för C++ API-referens
description: "Vertikal justering av grupptecken. Anger justeringen av objektet i förhållande till baslinjen. Till exempel, när grupptecknet är ovanför objektet, betyder VerticalJustification av Top att objektets topp ligger på baslinjen; när VerticalJustification är inställd på Bottom ligger objektets botten på baslinjen Standard: Bottom för Position=Top, och Top för Position=Bottom"
type: docs
weight: 66
url: /sv/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() metod

Vertikal justering av grupptecken. Anger justeringen av objektet i förhållande till baslinjen. Till exempel, när grupptecknet är ovanför objektet, betyder VerticalJustification av Top att toppen av objektet ligger på baslinjen; när VerticalJustification är inställd på Bottom ligger botten av objektet på baslinjen Standard: Bottom för Position=Top, och Top för Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## Anmärkningar

Exempel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Se också

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Klass [IMathGroupingCharacter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)