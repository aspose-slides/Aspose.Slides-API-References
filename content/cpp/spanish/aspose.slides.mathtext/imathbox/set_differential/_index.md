---
title: set_Differential()
second_title: Referencia de API de Aspose.Slides para C++
description: "Diferencial. Cuando es verdadero, el cuadro actúa como un diferencial (p. ej., \\uD835\\uDC51\\uD835\\uDC65 en un integrando), y recibe el espaciado horizontal apropiado para el diferencial matemático. Predeterminado: false"
type: docs
weight: 79
url: /es/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) método


Diferencial. Cuando es verdadero, el cuadro actúa como un diferencial (p. ej., \\uD835\\uDC51\\uD835\\uDC65 en un integrando), y recibe el espaciado horizontal apropiado para el diferencial matemático. Predeterminado: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
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

* Clase [IMathBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)