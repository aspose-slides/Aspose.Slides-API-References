---
title: get_Degree()
second_title: Referencia de API de Aspose.Slides para C++
description: Argumento Degree
type: docs
weight: 14
url: /es/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() método


Argumento Degree

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Observaciones


Ejemplo: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathRadical](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)