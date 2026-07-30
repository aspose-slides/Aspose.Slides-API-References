---
title: get_BaseJustification()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Určuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán ke spodnímu, hornímu nebo středovému okraji objektu pole. Výchozí hodnota: Center"
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() metoda

Specifikuje zarovnání pole vzhledem k okolnímu textu. Text mimo pole může být zarovnán ke spodnímu, hornímu nebo středovému okraji objektu pole. Výchozí hodnota: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
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