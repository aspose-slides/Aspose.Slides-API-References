---
title: get_Base()
second_title: Referencia de API de Aspose.Slides para C++
description: Argumento Base
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathbar/get_base/
---
## MathBar::get_Base() método

Argumento Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBar::get_Base() override
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
* Clase [MathBar](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)