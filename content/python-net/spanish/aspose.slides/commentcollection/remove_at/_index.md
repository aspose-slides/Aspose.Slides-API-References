---
title: remove_at method
second_title: Aspose.Slides para Python mediante la API .NET
description: 
type: docs
url: /es/aspose.slides/commentcollection/remove_at/
weight: 80
---
## remove_at(self, index) {#int}
Elimina el elemento en el índice especificado de una colección.

```python
def remove_at(self, index):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero del elemento a eliminar. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | El índice es menor que 0 o el índice es igual o mayor que Count |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Se lanza si el comentario ya ha sido eliminado. |

### Véase también
* clase [`CommentCollection`](/slides/python-net/es/aspose.slides/commentcollection)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)