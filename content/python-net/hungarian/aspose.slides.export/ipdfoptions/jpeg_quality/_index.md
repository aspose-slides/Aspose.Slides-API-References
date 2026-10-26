---
title: jpeg_quality property
second_title: Aspose.Slides Pythonhoz a .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.export/ipdfoptions/jpeg_quality/
weight: 150
---
## jpeg_quality tulajdonság
Visszaad vagy beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban.
            Olvasás/írás **int**.


### Megjegyzések

Csak akkor van hatása, ha a dokumentum JPEG képeket tartalmaz.


Használd ezt a tulajdonságot a képek minőségének lekérdezésére vagy beállítására egy dokumentum mentésekor PDF formátumban.
            Az érték 0 és 100 között változhat, ahol a 0 legrosszabb minőséget, de legnagyobb tömörítést, a 100 pedig a legjobb minőséget, de legkisebb tömörítést jelent.


Az alapértelmezett érték **100** .

### Definíció:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### Lásd még
* osztály [`IPdfOptions`](/slides/python-net/hu/aspose.slides.export/ipdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)