---
title: set_Differential()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Diferencial Cuando es verdadero, la caja actúa como una diferencial (p. ej., \\uD835\\uDC51\\uD835\\uDC65 en un integrando), y recibe el espaciado horizontal apropiado para la diferencial matemática. Predeterminado: false"
type: docs
weight: 79
url: /es/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) método

Diferencial Cuando es verdadero, la caja actúa como una diferencial (p. ej., \\uD835\\uDC51\\uDC65 en un integrando), y recibe el espaciado horizontal apropiado para la diferencial matemática. Predeterminado: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
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