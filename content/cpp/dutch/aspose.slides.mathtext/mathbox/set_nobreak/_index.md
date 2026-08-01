---
title: set_NoBreak()
second_title: Aspose.Slides voor C++ API-referentie
description: "Geen onderbreking Deze eigenschap specificeert de \"unbreakable\"-eigenschap op de objectdoos. Wanneer true, kunnen er geen regeleinden optreden binnen de doos. Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is gespecificeerd, kunnen er onderbrekingen binnen de doos optreden. Standaard: true"
type: docs
weight: 53
url: /nl/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) methode

Geen onderbreking Deze eigenschap specificeert de "unbreakable"-eigenschap op de objectdoos. Wanneer true, kunnen er geen regeleinden optreden binnen de doos. Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is gespecificeerd, kunnen er onderbrekingen binnen de doos optreden. Standaard: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
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