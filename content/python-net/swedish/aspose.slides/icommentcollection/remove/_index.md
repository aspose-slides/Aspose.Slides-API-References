---
title: remove method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/icommentcollection/remove/
weight: 60
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
| **RuntimeError(Proxy error(ArgumentNullException))** | Om comment är `None` |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om comment redan har tagits bort. |



### Se även
* klass [`IComment`](/slides/python-net/sv/aspose.slides/icomment)
* klass [`ICommentCollection`](/slides/python-net/sv/aspose.slides/icommentcollection)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)