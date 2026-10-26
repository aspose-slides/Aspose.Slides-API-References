---
title: get_Name()
second_title: Referencia de la API de Aspose.Slides para C++
description: Nombre de la función Por ejemplo, los nombres de funciones son sin y cos
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() método


Nombre de la función Por ejemplo, los nombres de funciones son sin y cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## Observaciones


Ejemplo: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathFunction](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)