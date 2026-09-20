---
title: remove_at method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/icommentcollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Tar bort elementet på det angivna indexet i en samling.

```python
def remove_at(self, index):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet för elementet som ska tas bort. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index är mindre än 0 eller index är lika med eller större än Count |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om kommentaren redan har tagits bort. |

### Se även
* klass [`ICommentCollection`](/slides/python-net/sv/aspose.slides/icommentcollection)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)