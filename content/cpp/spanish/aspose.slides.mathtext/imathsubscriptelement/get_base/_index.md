---
title: get_Base()
second_title: Referencia de la API de Aspose.Slides para C++
description: Argumento base
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathsubscriptelement/get_base/
---
## IMathSubscriptElement::get_Base() método

argumento Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Base()=0
```

## Observaciones

Ejemplo:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto baseElem = subscriptElement->get_Base();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathSubscriptElement](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)