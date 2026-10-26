---
title: get_Count()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el número de elementos realmente contenidos en la colección. Solo lectura int32_t.
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathelementcollection/get_count/
---
## IMathElementCollection::get_Count() método


Obtiene el número de elementos realmente contenidos en la colección. Solo lectura **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::get_Count()=0
```

## Observaciones


Ejemplo: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = collection->get_Count();
```

## Ver también

* Clase [IMathElementCollection](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)