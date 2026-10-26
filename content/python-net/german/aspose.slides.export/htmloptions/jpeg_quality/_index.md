---
title: jpeg_quality property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/htmloptions/jpeg_quality/
weight: 90
---
## jpeg_quality Eigenschaft
Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt.
            Lesen/Schreiben **int**.


### Hinweise

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.


Verwenden Sie diese Eigenschaft, um die Qualität der Bilder in einem Dokument beim Speichern im PDF-Format abzurufen oder festzulegen.
            Der Wert kann von 0 bis 100 variieren, wobei 0 die schlechteste Qualität aber höchste Kompression bedeutet und 100 die beste Qualität aber minimale Kompression.


Der Standardwert ist **95** .

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
* Klasse [`HtmlOptions`](/slides/python-net/de/aspose.slides.export/htmloptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)