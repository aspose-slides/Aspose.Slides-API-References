---
title: jpeg_quality property
second_title: Aspose.Slides a Python számára .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.export/htmloptions/jpeg_quality/
weight: 90
---
## jpeg_quality tulajdonság
Visszaad vagy beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban.
            Olvasás/írás **int**.

### Megjegyzés

Csak akkor van hatása, ha a dokumentum JPEG képeket tartalmaz.

Használd ezt a tulajdonságot a képek minőségének lekéréséhez vagy beállításához egy dokumentumban PDF formátumban történő mentéskor.
            Az érték 0 és 100 között változhat, ahol a 0 a legrosszabb minőséget, de a legnagyobb tömörítést jelenti, és a 100 a legjobb minőséget, de a legkisebb tömörítést.

Az alapértelmezett érték **95**.

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
* osztály [`HtmlOptions`](/slides/python-net/hu/aspose.slides.export/htmloptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)