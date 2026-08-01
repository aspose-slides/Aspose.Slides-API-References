---
title: get_OperatorEmulator()
second_title: Aspose.Slides voor C++ API Referentie
description: "Operator Emulator. Wanneer true, gedraagt de box en de inhoud zich als één enkele operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operators. Operator Emulators worden vaak gebruikt wanneer een of meer glyphs samen een operator vormen, zoals '=='. Standaardwaarde: false"
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() methode


Operator Emulator. Wanneer true, gedraagt de box en de inhoud zich als één enkele operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operators. Operator Emulators worden vaak gebruikt wanneer een of meer glyphs samen een operator vormen, zoals '=='. Standaardwaarde: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
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