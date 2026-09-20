---
title: save_metafiles_as_png property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png proprietà
True per convertire tutti i metafile usati in una presentazione in immagini PNG.
Lettura/scrittura **bool**.

### Osservazioni

Il valore predefinito è **true** .
Il documento PDF può contenere grafica vettoriale e immagini raster. 
Se SaveMetafilesAsPng è impostato su true allora l'immagine Metafile di origine viene convertita in formato Png e salvata nel Pdf come immagine raster. Se SaveMetafilesAsPng è impostato su false allora il Metafile di origine viene convertito in grafica vettoriale Pdf. Ogni approccio ha vantaggi e svantaggi. Per esempio, se il Metafile viene convertito in PNG, può verificarsi una perdita di qualità durante il ridimensionamento del documento risultante. Se il Metafile viene convertito in grafica vettoriale Pdf, possono verificarsi problemi di prestazioni nello strumento di visualizzazione Pdf.

### Definizione:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### Vedi anche
* classe [`PdfOptions`](/slides/python-net/it/aspose.slides.export/pdfoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)