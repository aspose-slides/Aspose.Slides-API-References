---
title: get_Base()
second_title: Referencia de API de Aspose.Slides para C++
description: Argumento base
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathbar/get_base/
---
## IMathBar::get_Base() método


Argumento Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBar::get_Base()=0
```

## Observaciones


Ejemplo: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathBar](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)