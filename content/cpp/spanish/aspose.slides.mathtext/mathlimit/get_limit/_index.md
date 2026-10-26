---
title: get_Limit()
second_title: Referencia de la API de Aspose.Slides para C++
description: Argumento del límite
type: docs
weight: 14
url: /es/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() método


Argumento del límite

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## Observaciones


Ejemplo: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathLimit](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)