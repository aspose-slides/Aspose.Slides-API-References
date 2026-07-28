---
title: set_Differential()
second_title: Aspose.Slides C++ API hivatkozás
description: "Differenciál. Ha igaz, a doboz differenciálként működik (például \\uD835\\uDC51\\uD835\\uDC65 egy integrandusban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciál számára. Alapértelmezett: false"
type: docs
weight: 79
url: /hu/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) metódus


Differenciál. Ha igaz, a doboz differenciálként működik (például \\uD835\\uDC51\\uD835\\uDC65 egy integrandusban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciál számára. Alapértelmezett: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
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