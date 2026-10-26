---
title: get_Base()
second_title: Referencia de la API de Aspose.Slides para C++
description: Argumento de la función
type: docs
weight: 14
url: /es/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() método


Argumento de la función

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## Observaciones


Ejemplo: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathFunction](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)