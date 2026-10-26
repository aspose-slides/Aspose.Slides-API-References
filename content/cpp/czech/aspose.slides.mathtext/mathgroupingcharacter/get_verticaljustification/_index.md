---
title: get_VerticalJustification()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Vertikální zarovnání skupinového znaku. Určuje zarovnání objektu vzhledem k základní lince. Například když je skupinový znak nad objektem, VerticalJustification of Top značí, že horní část objektu leží na základní lince; když je VerticalJustification nastaveno na Bottom, spodní část objektu je na základní lince. Výchozí: Bottom pro Position=Top a Top pro Position=Bottom"
type: docs
weight: 66
url: /cs/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() metoda

Vertikální zarovnání skupinového znaku. Určuje zarovnání objektu vzhledem k základní lince. Například když je skupinový znak nad objektem, VerticalJustification hodnoty Top značí, že horní část objektu leží na základní lince; když je VerticalJustification nastaveno na Bottom, spodní část objektu je na základní lince. Výchozí: Bottom pro Position=Top a Top pro Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
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
* Knihovna [Aspose.Slides](../../../)