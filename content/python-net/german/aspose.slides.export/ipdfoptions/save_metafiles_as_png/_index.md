---
title: save_metafiles_as_png property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png Eigenschaft
True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren.
            Lese-/Schreib **bool**.


### Anmerkungen

Standard ist **true** .
            Pdf-Dokument kann Vektorgrafiken und Rasterbilder enthalten. 
            Wenn SaveMetafilesAsPng auf true gesetzt ist, wird das Quell-Metafile-Bild in das Png-Format konvertiert und als Raster-Bild im Pdf gespeichert. Wenn SaveMetafilesAsPng auf false gesetzt ist, wird das Quell-Metafile in Pdf-Vektorgrafiken konvertiert. Jeder Ansatz hat Vor- und Nachteile. Beispielsweise kann beim Konvertieren des Metafile in PNG bei der Skalierung des resultierenden Dokuments ein Qualitätsverlust auftreten. Beim Konvertieren des Metafile in Pdf-Vektorgrafiken können Leistungsprobleme im Pdf-Betrachtungsprogramm auftreten.

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
* Klasse [`IPdfOptions`](/slides/python-net/de/aspose.slides.export/ipdfoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)