---
title: remove_at method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/commentauthorcollection/remove_at/
weight: 60
---
## remove_at(self, index) {#int}
Elimina el autor en el índice especificado de la colección.

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
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Se lanza si el autor ya ha sido eliminado. |

### Ver también
* clase [`CommentAuthorCollection`](/slides/python-net/es/aspose.slides/commentauthorcollection)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)