---
title: get_Numerator()
second_title: Referencia de API de Aspose.Slides para C++
description: Numerador
type: docs
weight: 27
url: /es/aspose.slides.mathtext/imathfraction/get_numerator/
---
## IMathFraction::get_Numerator() método


Numerador

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Numerator()=0
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
* Clase [IMathFraction](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)