---
title: copy_to method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Átmásolja a **System.Collections.Generic.ICollection`1** elemeit egy **System.Array**-ba, egy adott **System.Array** indexnél kezdve.


```python
def copy_to(self, array, array_index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| array | **List[IPortion]** | A egydimenziós **System.Array**, amely a **System.Collections.Generic.ICollection`1**-ből átmásolt elemek célja. A **System.Array**-nak nullaalapú indexelése kell legyen. |
| array_index | **int** | A nullaalapú index a `array`-ben, ahol a másolás kezdődik. |

### Exceptions

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` None értékű. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` kisebb, mint 0. |
| **RuntimeError(Proxy error(ArgumentException))** | A forrás **System.Collections.Generic.ICollection`1** elemeinek száma nagyobb, mint a rendelkezésre álló hely `array_index`-től a cél `array` végéig. |


### See Also
* osztály [`PortionCollection`](/slides/python-net/hu/aspose.slides/portioncollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)