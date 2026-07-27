---
title: get_Arguments()
second_title: Referencia de la API de Aspose.Slides for C++
description: Conjunto de elementos del array
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() método


Conjunto de elementos del array

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
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
* Clase [IMathArray](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)