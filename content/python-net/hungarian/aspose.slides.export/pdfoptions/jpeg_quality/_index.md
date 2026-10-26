---
title: jpeg_quality property
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.export/pdfoptions/jpeg_quality/
weight: 160
---
## jpeg_quality tulajdonság
Értéket ad vissza vagy állít be, amely meghatározza a JPEG képek minőségét a PDF dokumentumban.
            Olvasás/írás **int**.


### Megjegyzés

Csak akkor van hatása, ha a dokumentum JPEG képeket tartalmaz.


Használja ezt a tulajdonságot a dokumentumban lévő képek minőségének lekérdezésére vagy beállítására PDF formátumban mentéskor.
            Az érték 0 és 100 között változhat, ahol a 0 a legrosszabb minőséget, de a maximális tömörítést jelenti, a 100 pedig a legjobb minőséget, de a minimális tömörítést.


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
* osztály [`PdfOptions`](/slides/python-net/hu/aspose.slides.export/pdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)