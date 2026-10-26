---
title: get_Denominator()
second_title: Referencia de API de Aspose.Slides para C++
description: Denominador
type: docs
weight: 40
url: /es/aspose.slides.mathtext/mathfraction/get_denominator/
---
## MathFraction::get_Denominator() método

Denominator

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Denominator() override
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
* Clase [MathFraction](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)