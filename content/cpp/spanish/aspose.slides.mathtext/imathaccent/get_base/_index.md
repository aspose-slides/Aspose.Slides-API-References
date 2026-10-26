---
title: get_Base()
second_title: Referencia de API de Aspose.Slides para C++
description: El argumento al que se aplicó el acento
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() método


El argumento al que se aplicó el acento

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## Observaciones


Ejemplo: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathAccent](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)