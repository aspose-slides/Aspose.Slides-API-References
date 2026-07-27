---
title: get_Base()
second_title: Referencia de API de Aspose.Slides para C++
description: El argumento al que se aplicó el acento
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() método

El argumento al que se aplicó el acento

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## Observaciones


Ejemplo: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathAccent](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)