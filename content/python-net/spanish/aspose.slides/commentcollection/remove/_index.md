---
title: remove method
second_title: Referencia API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/commentcollection/remove/
weight: 70
---
## remove(self, comment) {#icomment}
Elimina la primera aparición del comentario especificado en una colección.

```python
def remove(self, comment):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| comment | [`IComment`](/slides/python-net/es/aspose.slides/icomment) | El comentario a eliminar de una colección. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Si comment es `None` |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Lanzada si comment ya está eliminado. |

### Véase también
* clase [`CommentCollection`](/slides/python-net/es/aspose.slides/commentcollection)
* clase [`IComment`](/slides/python-net/es/aspose.slides/icomment)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)