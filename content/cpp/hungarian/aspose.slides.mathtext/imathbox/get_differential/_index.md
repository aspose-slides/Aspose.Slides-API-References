---
title: get_Differential()
second_title: Aspose.Slides for C++ API referencia
description: "Differenciál. Ha igaz, a doboz differenciálként működik (például \\uD835\\uDC51\\uD835\\uDC65 egy integrandusban), és a matematikai differenciálhoz megfelelő vízszintes térközt kap. Alapértelmezett: false"
type: docs
weight: 66
url: /hu/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() metódus

Differenciál. Ha igaz, a doboz differenciálként viselkedik (e.g., \\uD835\\uDC51\\uD835\\uDC65 in an integrand), és a matematikai differenciálhoz megfelelő vízszintes térközt kap. Alapértelmezett: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
```

## Megjegyzések

Példa: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Lásd még

* Osztály [IMathBox](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)