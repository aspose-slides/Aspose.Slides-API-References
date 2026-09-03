---
title: get_image method
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image {#}
Visszaad egy képet a bekezdésről.

### Returns
Egy kép, amely a renderelt bekezdést tartalmazza, vagy **None**, ha a bekezdést nem találja meg a szülőgyűjteményben, nincs érvényes megjelenítési határa, vagy hiba történik a kép renderelése közben.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Visszaad egy képet a bekezdésről a megadott mérettel.

### Returns
Egy kép, amely a renderelt bekezdést tartalmazza, vagy **None**, ha a bekezdést nem találja meg a szülőgyűjteményben, nincs érvényes megjelenítési határa, vagy hiba történik a kép renderelése közben.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| scale_x | **float** | A bekezdés képre alkalmazott vízszintes méretezési tényező. |
| scale_y | **float** | A bekezdés képre alkalmazott függőleges méretezési tényező. |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`IParagraph`](/slides/python-net/hu/aspose.slides/iparagraph)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)