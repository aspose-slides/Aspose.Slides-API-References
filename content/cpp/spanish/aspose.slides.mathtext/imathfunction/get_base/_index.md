---
title: get_Base()
second_title: Referencia de API de Aspose.Slides para C++
description: Argumento de la función
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() método

Argumento de la función

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## Comentarios

Ejemplo:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathFunction](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)