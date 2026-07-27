---
title: get_UpperLimit()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica el límite superior o inferior
type: docs
weight: 27
url: /es/aspose.slides.mathtext/imathlimit/get_upperlimit/
---
## IMathLimit::get_UpperLimit() método


Especifica el límite superior o inferior

```cpp
virtual bool Aspose::Slides::MathText::IMathLimit::get_UpperLimit()=0
```

## Observaciones


Ejemplo: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Ver también

* Clase [IMathLimit](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)