---
title: save_metafiles_as_png property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png Eigenschaft
True, um alle in einer Präsentation verwendeten Metafiles in die PNG-Bilder zu konvertieren.
            Lesen/Schreiben **bool**.


### Bemerkungen

Standard ist **true** .
            Pdf-Dokument kann Vektorgrafiken und Rasterbilder enthalten. 
            Wenn SaveMetafilesAsPng auf true gesetzt ist, wird das Quell-Metafile-Bild in das Png-Format konvertiert und als Rasterbild im Pdf gespeichert. Wenn SaveMetafilesAsPng auf false gesetzt ist, wird das Quell-Metafile in Pdf-Vektorgrafiken konvertiert. Jeder Ansatz hat Vor- und Nachteile. Zum Beispiel kann bei der Konvertierung von Metafile zu PNG beim Skalieren des resultierenden Dokuments ein Qualitätsverlust auftreten. Wenn Metafile zu Pdf-Vektorgrafiken konvertiert wird, können Leistungsprobleme im Pdf-Betrachtungsprogramm auftreten.

### Definition:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```


### Siehe auch
* Klasse [`PdfOptions`](/slides/python-net/de/aspose.slides.export/pdfoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)