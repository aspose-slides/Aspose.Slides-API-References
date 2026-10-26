---
title: get_Base()
second_title: Referencia de la API de Aspose.Slides para C++
description: Argumento base
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() método


Argumento base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## Observaciones


Ejemplo: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // raíz cúbica
auto baseElem = radical->get_Base();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathRadical](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)