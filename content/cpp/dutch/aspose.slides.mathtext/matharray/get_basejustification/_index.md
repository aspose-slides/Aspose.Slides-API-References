---
title: get_BaseJustification()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert de uitlijning van de array ten opzichte van de omliggende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het midden van een array-object. Standaardwaarde: Center"
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() methode


Specificeert de uitlijning van de array ten opzichte van de omliggende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het midden van een array-object. Standaardwaarde: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Zie ook

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Klasse [MathArray](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)