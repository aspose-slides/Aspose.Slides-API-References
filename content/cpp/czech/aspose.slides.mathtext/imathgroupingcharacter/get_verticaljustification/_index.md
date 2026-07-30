---
title: get_VerticalJustification()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Vertikální zarovnání skupinového znaku. Udává zarovnání objektu vzhledem k základní lince. Například když je skupinový znak nad objektem, VerticalJustification of Top znamená, že horní část objektu leží na základní lince; když je VerticalJustification nastaveno na Bottom, spodní část objektu je na základní lince. Výchozí: Bottom pro Position=Top a Top pro Position=Bottom"
type: docs
weight: 66
url: /cs/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() metoda


Vertikální zarovnání skupinového znaku. Udává zarovnání objektu vzhledem k základní čáře. Například když je skupinový znak nad objektom, VerticalJustification s hodnotou Top značí, že horní část objektu leží na základní čáře; když je VerticalJustification nastaveno na Bottom, spodní část objektu je na základní čáře. Výchozí: Bottom pro Position=Top a Top pro Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## Poznámky


Příklad: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Viz také

* Výčet [MathTopBotPositions](../../mathtopbotpositions/)
* Třída [IMathGroupingCharacter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)