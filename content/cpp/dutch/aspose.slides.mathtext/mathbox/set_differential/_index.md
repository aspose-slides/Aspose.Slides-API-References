---
title: set_Differential()
second_title: Aspose.Slides voor C++ API-referentie
description: "Differential Wanneer true, de box fungeert als een differentiaal (bijv., \\uD835\\uDC51\\uD835\\uDC65 in een integrand), en krijgt de juiste horizontale spatiëring voor het wiskundige differentiaal. Standaard: false"
type: docs
weight: 79
url: /nl/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) methode

Differential Wanneer true, de box fungeert als een differentiaal (bijv., \\uD835\\uDC51\\uDC65 in een integrand), en krijgt de juiste horizontale spatiëring voor het wiskundige differentiaal. Standaard: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Zie ook

* Klasse [MathBox](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)