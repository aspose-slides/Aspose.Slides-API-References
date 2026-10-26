---
title: get_Differential()
second_title: Aspose.Slides voor C++ API-referentie
description: "Differentiaal Wanneer true, de box functioneert als een differentiaal (e.g., \\uD835\\uDC51\\uD835\\uDC65 in een integrand), en ontvangt de juiste horizontale spatiëring voor het wiskundige differentiaal. Default: false"
type: docs
weight: 66
url: /nl/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() method


Differentiaal Wanneer true, de box functioneert als een differentiaal (e.g., \\uD835\\uDC51\\uDC65 in een integrand), en ontvangt de juiste horizontale spatiëring voor het wiskundige differentiaal. Default: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
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