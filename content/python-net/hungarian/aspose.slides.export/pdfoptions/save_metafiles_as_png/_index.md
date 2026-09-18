---
title: save_metafiles_as_png property
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozás segítségével
description: 
type: docs
url: /hu/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png tulajdonság
True to convert all metafiles used in a presentation to the PNG images.
            Olvasás/írás **bool**.


### Megjegyzés

Az alapértelmezett érték **true** .
            Pdf dokumentum tartalmazhat vektorgrafikákat és raszteres képeket. 
            Ha SaveMetafilesAsPng értéke **true**, akkor a forrás Metafile 
            kép Png formátumba konvertálódik, és raster képként kerül a Pdf-be. Ha SaveMetafilesAsPng értéke **false**, akkor a forrás Metafile 
            Pdf vektorgrafikává alakul. Minden megközelítésnek vannak előnyei 
            és hátrányai. Például, ha Metafile PNG formátumba konvertálódik, 
            akkor a dokumentum méretezésekor minőségromlás lehetséges. Ha Metafile Pdf vektorgrafikává alakul, 
            akkor a Pdf megtekintő eszközben teljesítményproblémák merülhetnek fel.

### Definíció:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```


### Lásd még
* osztály [`PdfOptions`](/slides/python-net/hu/aspose.slides.export/pdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)