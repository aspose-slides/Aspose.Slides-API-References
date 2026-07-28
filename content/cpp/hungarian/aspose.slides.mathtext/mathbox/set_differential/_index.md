---
title: set_Differential()
second_title: Aspose.Slides C++ API referencia
description: "Differential Ha igaz, a doboz differenciálként működik (e.g., \\uD835\\uDC51\\uD835\\uDC65 egy integrálban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciálhoz. Alapértelmezett: false"
type: docs
weight: 79
url: /hu/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) metódus


Differential Ha igaz, a doboz differenciálként működik (e.g., \\uD835\\uDC51\\uD835\\uDC65 in an integrand), és megkapja a megfelelő vízszintes távolságot a matematikai differenciál számára. Default: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
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
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)