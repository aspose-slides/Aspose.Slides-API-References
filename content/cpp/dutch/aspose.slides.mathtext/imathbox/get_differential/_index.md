---
title: get_Differential()
second_title: Aspose.Slides voor C++ API-referentie
description: "Differentiaal. Wanneer true, gedraagt de box zich als een differentiaal (bijv., \\uD835\\uDC51\\uD835\\uDC65 in een integrand), en ontvangt de juiste horizontale spatiëring voor het wiskundige differentiaal. Standaard: false"
type: docs
weight: 66
url: /nl/aspose.slides.mathtext/imathbox/get_differential/
---
## IMMathBox::get_Differential() methode


Differential. Wanneer true, gedraagt de box zich als een differentiaal (bijv., \\uD835\\uDC51\\uDC65 in een integrand), en ontvangt de juiste horizontale spatiëring voor het wiskundige differentiaal. Standaard: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
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

* Klasse [IMathBox](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)