---
title: set_NoBreak()
second_title: Aspose.Slides voor C++ API-referentie
description: "Geen onderbreking. Deze eigenschap specificeert de \"ononderbreekbare\" eigenschap van de objectdoos. Wanneer true, kunnen er geen regelonderbrekingen binnen de doos optreden. Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is gespecificeerd, kunnen er onderbrekingen binnen de doos optreden. Standaard: true"
type: docs
weight: 53
url: /nl/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) methode

Geen onderbreking. Deze eigenschap specificeert de "ononderbreekbare" eigenschap van de objectdoos. Wanneer true, kunnen er geen regeleindeonderbrekingen binnen de doos optreden. Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. Wanneer dit element niet is gespecificeerd, kunnen onderbrekingen binnen de doos optreden. Standaard: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## Opmerkingen

Voorbeeld:
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Zie ook

* Klasse [IMathBox](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)