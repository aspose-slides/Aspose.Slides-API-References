---
title: get_BaseJustification()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert de uitlijning van de array ten opzichte van de omliggende tekst. Tekst buiten de array kan uitgelijnd worden met de onderkant, bovenkant of het midden van een array-object. Standaardwaarde: Center"
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() methode

Specificeert de uitlijning van de array ten opzichte van de omliggende tekst. Tekst buiten de array kan uitgelijnd worden met de onderkant, bovenkant of het midden van een array-object. Standaardwaarde: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## Opmerkingen

Example: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Zie ook

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Klasse [IMathArray](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)