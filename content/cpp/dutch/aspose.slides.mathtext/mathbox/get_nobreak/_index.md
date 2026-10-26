---
title: get_NoBreak()
second_title: Aspose.Slides voor C++ API-referentie
description: "Geen onderbreking Deze eigenschap specificeert de \"ononderbreekbare\" eigenschap op de objectbox. Wanneer true, kunnen er geen regeleinden binnen de box voorkomen. Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is gespecificeerd, kunnen er onderbrekingen binnen de box voorkomen. Standaard: true"
type: docs
weight: 40
url: /nl/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() methode

Geen onderbreking Deze eigenschap geeft de \"unbreakable\" eigenschap op de objectbox aan. Wanneer true, kunnen er geen regeleinden binnen de box voorkomen. Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is gespecificeerd, kunnen er onderbrekingen binnen de box voorkomen. Standaard: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## Opmerkingen

Voorbeeld: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Zie ook

* Klasse [MathBox](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)