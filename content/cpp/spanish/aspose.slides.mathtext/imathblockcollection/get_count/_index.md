---
title: get_Count()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene el número de elementos realmente contenidos en la colección. Solo lectura int32_t.
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() método

Obtiene el número de elementos realmente contenidos en la colección. Solo lectura **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Observaciones

Ejemplo:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## Ver también

* Clase [IMathBlockCollection](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)