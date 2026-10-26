---
title: Clear()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina todos los elementos de la colección.
type: docs
weight: 118
url: /es/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() método


Removes all elements from the collection.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Observaciones


Ejemplo: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Ver también

* Clase [IMathBlockCollection](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)