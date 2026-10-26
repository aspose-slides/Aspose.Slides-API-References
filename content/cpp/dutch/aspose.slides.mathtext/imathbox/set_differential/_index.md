---
title: set_Differential()
second_title: Aspose.Slides for C++ API Referentie
description: "Differentiaal. Wanneer true, functioneert de box als een differentiaal (bijv., \\uD835\\uDC51\\uD835\\uDC65 in een integrand), en ontvangt de juiste horizontale spatiëring voor het wiskundige differentiaal. Standaard: false"
type: docs
weight: 79
url: /nl/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) methode


Differentiaal. Wanneer true, functioneert de box als een differentiaal (bijv., \\uD835\\uDC51\\uD835\\uDC65 in een integrand), en ontvangt de juiste horizontale spatiëring voor het wiskundige differentiaal. Standaard: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
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