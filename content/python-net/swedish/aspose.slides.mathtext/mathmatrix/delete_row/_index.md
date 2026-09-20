---
title: delete_row method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Tar bort den angivna raden


```python
def delete_row(self, row_index):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| row_index | **int** | Det nollbaserade indexet för raden som ska tas bort. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | När du försöker ta bort den sista enda raden i matrisen |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Om rowIndex är mindre än noll eller större än eller lika med RowCount |



### Se även
* klass [`MathMatrix`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)