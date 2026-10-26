---
title: get_Arguments()
second_title: Referencia de API de Aspose.Slides para C++
description: El conjunto de elementos del arreglo
type: docs
weight: 1
url: /es/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() método


El conjunto de elementos del arreglo

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## Observaciones


Ejemplo: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElementCollection](../../imathelementcollection/)
* Clase [MathArray](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)