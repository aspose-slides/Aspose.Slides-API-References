---
title: remove_at method
second_title: Aspose.Slides para Python mediante la API .NET
description: 
type: docs
url: /es/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
Elimina el elemento en el índice especificado de la colección.

```python
def remove_at(self, index):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero del elemento a eliminar. |

### Observaciones

Para evitar lanzar la PptxEditException, compruebe la propiedad HasDependingSlides del maestro antes.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Se lanza si el maestro a eliminar se usa en la presentación (su propiedad HasDependingSlides es verdadera). |

### Ver también
* clase [`MasterSlideCollection`](/slides/python-net/es/aspose.slides/masterslidecollection)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)