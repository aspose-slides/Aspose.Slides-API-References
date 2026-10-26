---
title: set_BaseJustification()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het midden van een array-object. Standaardwaarde: Center"
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) methode

Specificeert de uitlijning van de array ten opzichte van de omringende tekst. Tekst buiten de array kan worden uitgelijnd met de onderkant, bovenkant of het midden van een array-object. Standaardwaarde: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## Opmerkingen

Voorbeeld: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Zie ook

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)