---
title: set_ExplicitBreak()
second_title: Aspose.Slides voor C++ API-referentie
description: "Expliciete onderbreking geeft aan of er een regeleinde aanwezig is aan het begin van het Box-object, zodat de regel wordt afgebroken aan het begin van het Box-object. Geeft het nummer van de operator op de vorige regel wiskundige tekst die wordt gebruikt als uitlijningspunt voor de huidige regel wiskundige tekst. Mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)"
type: docs
weight: 131
url: /nl/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) methode

Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box object, zodat de regel wordt afgebroken aan het begin van het Box object. Geeft het nummer van de operator op de vorige regel wiskundige tekst dat moet worden gebruikt als uitlijningspunt voor de huidige regel wiskundige tekst. Mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## Opmerkingen

Voorbeeld:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Zie ook

* Klasse [MathBox](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)