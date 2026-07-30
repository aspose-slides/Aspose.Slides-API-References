---
title: set_VerticalJustification()
second_title: Aspose.Slides pro C++ API Reference
description: "Vertikální zarovnání skupinového znaku. Určuje zarovnání objektu vzhledem k základní lince. Například když je skupinový znak nad objektem, Vertikální zarovnání Top znamená, že horní část objektu leží na základní lince; když je Vertikální zarovnání nastaveno na Bottom, spodní část objektu je na základní lince Výchozí: Bottom pro Position=Top a Top pro Position=Bottom"
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) metoda

Vertikální zarovnání skupinového znaku. Určuje zarovnání objektu vzhledem k základní lince. Například když je skupinový znak nad objektem, Vertikální zarovnání Top znamená, že horní část objektu leží na základní lince; když je Vertikální zarovnání nastaveno na Bottom, spodní část objektu je na základní lince. Výchozí: Bottom pro Position=Top a Top pro Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## Poznámky

Příklad: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Viz také

* Enumerace [MathTopBotPositions](../../mathtopbotpositions/)
* Třída [IMathGroupingCharacter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)