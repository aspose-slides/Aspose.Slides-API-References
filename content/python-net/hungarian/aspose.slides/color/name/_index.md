---
title: name property
second_title: Aspose.Slides a Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/color/name/
weight: 190
---
## name tulajdonság
A szín nevét adja vissza.<br/>            Egy névvel ellátott szín esetén (például egy `Color.red` névkonstans, vagy egy [`from_name`](/slides/python-net/hu/aspose.slides/color/from_name/)-val létrehozott szín) a .NET név kerül visszaadásra, például `"Red"` vagy `"LightBlue"`.<br/>            Bármely más szín esetén az ARGB érték kerül visszaadásra kisbetűs hexadecimális formában, nulla kitöltés nélkül, például `"ffff0000"`. `Color.empty.name` értéke `"0"`.
Csak olvasható **str**.

### Definíció:
```python
@property
def name(self):
    ...
```


### Lásd még
* osztály [`Color`](/slides/python-net/hu/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)