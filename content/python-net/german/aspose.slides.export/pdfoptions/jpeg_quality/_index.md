---
title: jpeg_quality property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/pdfoptions/jpeg_quality/
weight: 160
---
## jpeg_quality Eigenschaft
Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt.
            Lesen/Schreiben **int**.


### Hinweise

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.


Verwenden Sie diese Eigenschaft, um die Qualität der Bilder in einem Dokument beim Speichern im PDF-Format zu erhalten oder festzulegen.
            Der Wert kann von 0 bis 100 variieren, wobei 0 die schlechteste Qualität aber maximalen Komprimierungsgrad bedeutet und 100 die beste Qualität aber minimalen Komprimierungsgrad.


Der Standardwert ist **100** .

### Definition:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### Siehe auch
* Klasse [`PdfOptions`](/slides/python-net/de/aspose.slides.export/pdfoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)