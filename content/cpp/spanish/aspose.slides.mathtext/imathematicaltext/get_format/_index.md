---
title: get_Format()
second_title: Referencia de API de Aspose.Slides para C++
description: Propiedades de formato de texto
type: docs
weight: 27
url: /es/aspose.slides.mathtext/imathematicaltext/get_format/
---
## IMathematicalText::get_Format() método


Propiedades de formato de texto

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::IMathematicalText::get_Format()=0
```

## Observaciones


Ejemplo: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPortionFormat](../../../aspose.slides/iportionformat/)
* Clase [IMathematicalText](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)