---
title: set_ExplicitBreak()
second_title: Aspose.Slides voor C++ API-referentie
description: "Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken aan het begin van het Box-object. Geeft het aantal van de operator op de vorige regel van wiskundige tekst dat als uitlijningspunt voor de huidige regel van wiskundige tekst moet worden gebruikt. Mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)"
type: docs
weight: 131
url: /nl/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) methode

Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box object, zodat de regel afbreekt aan het begin van het Box object. Geeft het aantal van de operator op de vorige regel van wiskundige tekst dat wordt gebruikt als uitlijningspunt voor de huidige regel van wiskundige tekst. Mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
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