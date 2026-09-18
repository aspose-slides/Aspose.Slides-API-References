---
title: copy_to method
second_title: Aspose.Slides a Python számára a .NET API Referencián keresztül
description: 
type: docs
url: /hu/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
Átmásolja a **System.Collections.Generic.ICollection`1** elemeit egy **System.Array**-ba, egy adott **System.Array** indexnél kezdve.


```python
def copy_to(self, array, array_index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| array | **List[IBehavior]** | Az egy dimenziós **System.Array**, amely a **System.Collections.Generic.ICollection`1**-ből másolt elemek célja. A **System.Array**-nek nulláról induló indexeléssel kell rendelkeznie. |
| array_index | **int** | A `array`-ben a nulláról induló index, ahol a másolás kezdődik. |

### Kivétel

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` kisebb, mint 0. |
| **RuntimeError(Proxy error(ArgumentException))** | A forrás **System.Collections.Generic.ICollection`1** elemeinek száma nagyobb, mint a `array_index`-től a cél `array` végéig rendelkezésre álló hely. |



### Lásd még
* osztály [`BehaviorCollection`](/slides/python-net/hu/aspose.slides.animation/behaviorcollection)
* modul [`aspose.slides.animation`](/slides/python-net/hu/aspose.slides.animation)
* könyvtár [`Aspose.Slides`](/slides/python-net)