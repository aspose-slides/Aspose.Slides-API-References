---
title: get_Base()
second_title: Referencia de la API de Aspose.Slides para C++
description: Argumento Base
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathphantom/get_base/
---
## MathPhantom::get_Base() método

Argumento Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathPhantom::get_Base() override
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
* Clase [MathPhantom](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)