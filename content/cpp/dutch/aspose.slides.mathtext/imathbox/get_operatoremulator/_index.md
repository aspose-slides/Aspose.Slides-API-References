---
title: get_OperatorEmulator()
second_title: Aspose.Slides voor C++ API-referentie
description: "Operator Emulator. Wanneer true, gedragen de box en de inhoud ervan zich als een enkele operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en uitgelijnd kan worden op andere operatoren. Operator Emulators worden vaak gebruikt wanneer één of meer glyphs combineren tot een operator, zoals '=='. Standaardwaarde: false"
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() methode


Operator Emulator. Wanneer true, gedragen de box en de inhoud ervan zich als een enkele operator en erven ze de eigenschappen van een operator. Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en uitgelijnd kan worden op andere operatoren. Operator Emulators worden vaak gebruikt wanneer één of meer glyphs combineren tot een operator, zoals '=='. Default value: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
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