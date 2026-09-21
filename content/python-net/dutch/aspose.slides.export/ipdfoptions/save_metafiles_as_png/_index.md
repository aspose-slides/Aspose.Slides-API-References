---
title: save_metafiles_as_png property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png eigenschap
True om alle metafiles die in een presentatie worden gebruikt naar PNG-afbeeldingen te converteren.
Lezen/schrijven **bool**.

### Opmerkingen
Standaard is **true**.
Pdf-document kan vectorafbeeldingen en rasterafbeeldingen bevatten.
            Als SaveMetafilesAsPng is set to true, dan source Metafile
            afbeelding wordt geconverteerd naar Png-formaat en opgeslagen in Pdf als een raster
            afbeelding. Als SaveMetafilesAsPng is set to false, dan source Metafile
            wordt geconverteerd naar Pdf vector graphics. Elke benadering heeft voordelen
            en nadelen. Bijvoorbeeld, als Metafile is geconverteerd naar PNG,
            dan kan enige kwaliteitsverlies optreden tijdens het resulterende
            document-schaalvergroting. Als Metafile is geconverteerd naar Pdf vector graphics,
            dan zijn prestatieproblemen in de Pdf-viewer mogelijk.

### Definitie:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### Zie ook
* klasse [`IPdfOptions`](/slides/python-net/nl/aspose.slides.export/ipdfoptions)
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)