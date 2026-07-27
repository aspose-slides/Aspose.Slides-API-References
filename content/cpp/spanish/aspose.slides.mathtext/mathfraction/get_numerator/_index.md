---
title: get_Numerator()
second_title: Referencia de API de Aspose.Slides para C++
description: Numerador
type: docs
weight: 27
url: /es/aspose.slides.mathtext/mathfraction/get_numerator/
---
## MathFraction::get_Numerator() método


Numerador

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Numerator() override
```

## Observaciones


Ejemplo: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathFraction](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)