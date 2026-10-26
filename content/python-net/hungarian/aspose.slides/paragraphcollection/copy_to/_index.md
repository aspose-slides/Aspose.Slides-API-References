---
title: copy_to method
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
Az **System.Collections.Generic.ICollection`1** elemeit egy **System.Array**-ba másolja, egy adott **System.Array** indexnél kezdve.

```python
def copy_to(self, array, array_index):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| array | **List[IParagraph]** | Az egydimenziós **System.Array**, amely a **System.Collections.Generic.ICollection`1**-ből másolt elemek célja. A **System.Array**-nak nullával kezdődő indexelése kell, hogy legyen. |
| array_index | **int** | A `array`-ben a másolás kezdőpontjának nullával kezdődő indexe. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` értéke None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` kisebb, mint 0. |
| **RuntimeError(Proxy error(ArgumentException))** | A forrás **System.Collections.Generic.ICollection`1** elemeinek száma nagyobb, mint az `array_index`-től a cél `array` végéig rendelkezésre álló hely. |

### Lásd még
* osztály [`ParagraphCollection`](/slides/python-net/hu/aspose.slides/paragraphcollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)