---
title: remove method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/commentcollection/remove/
weight: 70
---
## remove(self, comment) {#icomment}
Tar bort den första förekomsten av den angivna kommentaren i en samling.

```python
def remove(self, comment):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| comment | [`IComment`](/slides/python-net/sv/aspose.slides/icomment) | Kommentaren som ska tas bort från en samling. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Om kommentaren är `None` |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om kommentaren redan har tagits bort. |

### Se även
* klass [`CommentCollection`](/slides/python-net/sv/aspose.slides/commentcollection)
* klass [`IComment`](/slides/python-net/sv/aspose.slides/icomment)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)