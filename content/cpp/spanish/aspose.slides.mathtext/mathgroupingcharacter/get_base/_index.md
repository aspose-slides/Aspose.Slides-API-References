---
title: get_Base()
second_title: Referencia de API de Aspose.Slides para C++
description: Argumento Base
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathgroupingcharacter/get_base/
---
## MathGroupingCharacter::get_Base() método


Argumento Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathGroupingCharacter::get_Base() override
```

## Observaciones


Ejemplo: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
auto baseArg = groupingCharacter->get_Base();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathGroupingCharacter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)