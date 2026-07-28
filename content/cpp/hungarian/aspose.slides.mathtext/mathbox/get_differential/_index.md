---
title: get_Differential()
second_title: Aspose.Slides C++ API-referencia
description: "Differential Ha igaz, a doboz differenciálként működik (például \\uD835\\uDC51\\uD835\\uDC65 egy integrandusban), és megkapja a megfelelő vízszintes térközt a matematikai differenciálhoz. Alapértelmezett: false"
type: docs
weight: 66
url: /hu/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() metódus

Differential Ha igaz, a doboz differenciálként viselkedik (például \\uD835\\uDC51\\uD835\\uDC65 egy integrandusban), és megkapja a megfelelő vízszintes térközt a matematikai differenciálhoz. Alapértelmezett: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
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

* Osztály [MathBox](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)