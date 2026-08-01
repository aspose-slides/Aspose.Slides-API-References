---
title: get_ExplicitBreak()
second_title: Aspose.Slides voor C++ API-referentie
description: "Explicit break specificeert of er een regeleinde is aan het begin van het Box-object, zodat de regel omslaat aan het begin van het Box-object. Specificeert het aantal van de operator op de vorige regel van wiskundige tekst dat als uitlijningspunt moet worden gebruikt voor de huidige regel van wiskundige tekst mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)"
type: docs
weight: 118
url: /nl/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() methode

Explicit break specificeert of er een regeleinde is aan het begin van het Box-object, zodat de regel omslaat aan het begin van het Box-object. Specificeert het aantal van de operator op de vorige regel van wiskundige tekst dat gebruikt moet worden als uitlijningspunt voor de huidige regel van wiskundige tekst mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Opmerkingen

Voorbeeld:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Zie ook

* Klasse [IMathBox](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)