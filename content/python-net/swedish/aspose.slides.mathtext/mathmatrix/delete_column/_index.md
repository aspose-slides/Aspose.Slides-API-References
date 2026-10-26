---
title: delete_column method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Raderar den angivna kolumnen


```python
def delete_column(self, column_index):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| column_index | **int** | Det nollbaserade indexet för kolumnen som ska raderas. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | När du försöker radera den sista enda kolumnen i matrisen |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Om columnIndex är mindre än noll eller större än eller lika med ColumnCount |



### Se även
* klass [`MathMatrix`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)