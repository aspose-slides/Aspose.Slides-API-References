---
title: save_metafiles_as_png property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png eigenschap
True om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen.
Lezen/schrijven **bool**.

### Opmerkingen

Standaard is **true**.
Pdf-document kan vectorafbeeldingen en rasterafbeeldingen bevatten. 
Als SaveMetafilesAsPng is ingesteld op true, wordt de bron-Metafile-afbeelding geconverteerd naar Png-formaat en opgeslagen in Pdf als een rasterafbeelding. Als SaveMetafilesAsPng is ingesteld op false, wordt de bron Metafile geconverteerd naar Pdf-vectorafbeeldingen. Elke aanpak heeft voordelen en nadelen. Bijvoorbeeld, als Metafile wordt geconverteerd naar PNG, is enige kwaliteitsverlies mogelijk tijdens het schalen van het resulterende document. Als Metafile wordt geconverteerd naar Pdf-vectorafbeeldingen, zijn prestatieproblemen in de Pdf-weergavetool mogelijk.

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
* klasse [`PdfOptions`](/slides/python-net/nl/aspose.slides.export/pdfoptions)
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)