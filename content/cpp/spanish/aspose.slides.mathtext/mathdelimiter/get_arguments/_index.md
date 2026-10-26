---
title: get_Arguments()
second_title: Aspose.Slides para la referencia de la API de C++
description: Uno o más elementos matemáticos separados por caracteres delimitadores
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() método


Uno o más elementos matemáticos separados por caracteres delimitadores

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## Observaciones


Ejemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElementCollection](../../imathelementcollection/)
* Clase [MathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)