---
title: get_Denominator()
second_title: Referencia de API de Aspose.Slides para C++
description: Denominador
type: docs
weight: 40
url: /es/aspose.slides.mathtext/imathfraction/get_denominator/
---
## IMathFraction::get_Denominator() método


Denominador

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Denominator()=0
```

## Observaciones


Ejemplo: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathFraction](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)