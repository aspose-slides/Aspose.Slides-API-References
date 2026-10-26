---
title: remove_at method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/icommentauthorcollection/remove_at/
weight: 60
---
## remove_at(self, index) {#int}
Tar bort författaren på det angivna indexet i samlingen.

```python
def remove_at(self, index):
    ...
```

| Parameter | Type | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet för elementet som ska tas bort. |

### Undantag

| Exception | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index är mindre än 0 eller index är lika med eller större än Count |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om författaren redan har tagits bort. |

### Se också
* klass [`ICommentAuthorCollection`](/slides/python-net/sv/aspose.slides/icommentauthorcollection)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)