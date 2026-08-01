---
title: set_BaseJustification()
second_title: Aspose.Slides voor C++ API Referentie
description: "Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het midden van een array object. Standaardwaarde: Center"
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) methode


Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het Center van een array-object. Standaardwaarde: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
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