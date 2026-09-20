---
title: save_metafiles_as_png property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png proprietà
True per convertire tutti i metafile usati in una presentazione nelle immagini PNG.
Lettura/scrittura **bool**.

### Note

Il valore predefinito è **true**.
Il documento Pdf può contenere grafica vettoriale e immagini raster.
Se SaveMetafilesAsPng è impostato su true, allora l'immagine Metafile di origine viene convertita al formato Png e salvata nel Pdf come immagine raster.
Se SaveMetafilesAsPng è impostato su false, allora il Metafile di origine viene convertito nella grafica vettoriale Pdf.
Ogni approccio ha vantaggi e svantaggi.
Ad esempio, se Metafile viene convertito in PNG, è possibile una perdita di qualità durante il ridimensionamento del documento risultante.
Se Metafile viene convertito nella grafica vettoriale Pdf, è possibile che si verifichino problemi di prestazioni nello strumento di visualizzazione Pdf.

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
* classe [`IPdfOptions`](/slides/python-net/it/aspose.slides.export/ipdfoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)