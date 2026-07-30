---
title: set_VerticalJustification()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Vertikální zarovnání skupinového znaku. Určuje zarovnání objektu vzhledem k základní lince. Například když je skupinový znak nad objektem, VerticalJustification of Top znamená, že horní část objektu leží na základní lince; když je VerticalJustification nastaveno na Bottom, spodní část objektu je na základní lince Default: Bottom pro Position=Top, a Top pro Position=Bottom"
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) metoda


Vertikální zarovnání skupinového znaku. Určuje zarovnání objektu vzhledem k základní lince. Například když je skupinový znak nad objektem, VerticalJustification of Top znamená, že horní část objektu leží na základní lince; když je VerticalJustification nastaveno na Bottom, spodní část objektu je na základní lince. Výchozí: Bottom pro Position=Top a Top pro Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## Poznámky


Příklad: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Viz také

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Třída [MathGroupingCharacter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)