---
title: set_OperatorEmulator()
second_title: Aspose.Slides voor C++ API-referentie
description: "Operator-emulator. Wanneer true, gedragen de doos en de inhoud zich als één operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operatoren. Operator-emulators worden vaak gebruikt wanneer één of meer glyphs combineren tot een operator, zoals '=='. Standaardwaarde: false"
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) methode


Operator-emulator. Wanneer true, gedragen de doos en de inhoud zich als één operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operatoren. Operator-emulators worden vaak gebruikt wanneer één of meer glyphs combineren tot een operator, zoals '=='. Standaardwaarde: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Zie ook

* Klasse [MathBox](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)