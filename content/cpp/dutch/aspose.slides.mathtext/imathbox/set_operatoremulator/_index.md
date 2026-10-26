---
title: set_OperatorEmulator()
second_title: Aspose.Slides voor C++ API-referentie
description: "Operator Emulator. Wanneer true, gedraagt de box en de inhoud zich als een enkele operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regelafbreking en kan worden uitgelijnd met andere operatoren. Operator Emulators worden vaak gebruikt wanneer één of meer glyphs combineren tot een operator, zoals '=='. Standaardwaarde: false"
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) methode

Operator Emulator. Wanneer true, gedraagt de box en de inhoud zich als een enkele operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regelafbreking en kan worden uitgelijnd met andere operatoren. Operator Emulators worden vaak gebruikt wanneer één of meer glyphs combineren tot een operator, zoals '=='. Standaardwaarde: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## Opmerkingen

Voorbeeld: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Zie ook

* Klasse [IMathBox](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)