---
title: get_Differential()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Diferencial Cuando es verdadero, el cuadro actúa como un diferencial (e.g., \\uD835\\uDC51\\uD835\\uDC65 en un integrando), y recibe el espaciado horizontal apropiado para el diferencial matemático. Predeterminado: false"
type: docs
weight: 66
url: /es/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() method


Diferencial Cuando es verdadero, el cuadro actúa como un diferencial (e.g., \\uD835\\uDC51\\uDC65 in an integrand), y recibe el espaciado horizontal apropiado para el diferencial matemático. Predeterminado: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
```

## Observaciones


Ejemplo: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Ver también

* Clase [MathBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)