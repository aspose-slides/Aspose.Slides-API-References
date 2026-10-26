---
title: get_Degree()
second_title: Referencia de API de Aspose.Slides para C++
description: Argumento de grado
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() método


Argumento de grado

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## Observaciones


Ejemplo: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // raíz cúbica
auto degreeElem = radical->get_Degree();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathRadical](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)