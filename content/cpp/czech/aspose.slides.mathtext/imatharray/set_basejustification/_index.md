---
title: set_BaseJustification()
second_title: Aspose.Slides pro C++ referenční dokumentace API
description: "Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán ke spodku, vrcholu nebo středu objektu pole. Výchozí hodnota: Center"
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) metoda


Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán ke spodku, vrcholu nebo středu objektu pole. Výchozí hodnota: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## Poznámky


Příklad: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Viz také

* Výčet [MathVerticalAlignment](../../mathverticalalignment/)
* Třída [IMathArray](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)