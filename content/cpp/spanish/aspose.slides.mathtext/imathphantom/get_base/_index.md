---
title: get_Base()
second_title: Referencia de API de Aspose.Slides para C++
description: Argumento base
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathphantom/get_base/
---
## IMathPhantom::get_Base() método


Argumento base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathPhantom::get_Base()=0
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathPhantom](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)