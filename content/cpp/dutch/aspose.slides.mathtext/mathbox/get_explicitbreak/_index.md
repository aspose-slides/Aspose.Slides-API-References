---
title: get_ExplicitBreak()
second_title: Aspose.Slides voor C++ API-referentie
description: "Explicit break geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken aan het begin van het box-object. Geeft het aantal van de operator op de vorige regel van wiskundige tekst dat moet worden gebruikt als het uitlijningspunt voor de huidige regel van wiskundige tekst. mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)"
type: docs
weight: 118
url: /nl/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() methode

Explicit break geeft aan of er een regeleinde is aan het begin van het Box-object, zodat de regel wordt afgebroken aan het begin van het box-object. Geeft het aantal van de operator op de vorige regel van wiskundige tekst dat moet worden gebruikt als het uitlijningspunt voor de huidige regel van wiskundige tekst. mogelijke waarden: 1..255 Standaard: 0 (geen expliciete onderbreking)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
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