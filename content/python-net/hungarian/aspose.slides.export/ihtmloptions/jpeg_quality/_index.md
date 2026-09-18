---
title: jpeg_quality property
second_title: Aspose.Slides for Python via .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.export/ihtmloptions/jpeg_quality/
weight: 80
---
## jpeg_quality tulajdonság
Visszaadja vagy beállítja azt az értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban.
            Olvasás/írás **int**.


### Megjegyzés

Csak akkor van hatása, ha a dokumentum JPEG képeket tartalmaz.


Használja ezt a tulajdonságot a dokumentumban lévő képek minőségének lekérdezéséhez vagy beállításához PDF formátumban való mentéskor.
            Az érték 0 és 100 között változhat, ahol a 0 a legrosszabb minőséget, de a maximális tömörítést, a 100 pedig a legjobb minőséget, de a minimális tömörítést jelenti.


Az alapértelmezett érték **95** .

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
* osztály [`IHtmlOptions`](/slides/python-net/hu/aspose.slides.export/ihtmloptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)