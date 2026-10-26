---
title: get_Limit()
second_title: Aspose.Slides para la referencia de la API de C++
description: Argumento de límite
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() método


Argumento de límite

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
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
* Clase [IMathLimit](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)