---
title: get_Format()
second_title: Referencia de la API de Aspose.Slides para C++
description: Propiedades de formato de texto
type: docs
weight: 27
url: /es/aspose.slides.mathtext/mathematicaltext/get_format/
---
## MathematicalText::get_Format() método


Propiedades de formato de texto

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::MathematicalText::get_Format() override
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
* Clase [MathematicalText](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)