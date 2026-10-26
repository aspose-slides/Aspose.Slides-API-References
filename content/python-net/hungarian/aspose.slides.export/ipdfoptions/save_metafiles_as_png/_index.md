---
title: save_metafiles_as_png property
second_title: Aspose.Slides a Python-hoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png tulajdonság
Igaz, ha az prezentációban használt összes metafájlt PNG képekké szeretné konvertálni.
Olvasás/írás **bool**.

### Megjegyzés

Az alapértelmezett **true** .
A Pdf dokumentum tartalmazhat vektoros grafikát és raszterképeket. 
Ha a SaveMetafilesAsPng igazra van állítva, akkor a forrás Metafile kép Png formátumba konvertálódik, és a Pdf-be raszterképként mentődik. Ha a SaveMetafilesAsPng hamisra van állítva, akkor a forrás Metafile Pdf vektoros grafikává konvertálódik. Minden megközelítésnek vannak előnyei és hátrányai. Például, ha a Metafile PNG-re van konvertálva, akkor a létrejövő dokumentum méretezése során előfordulhat minőségveszteség. Ha a Metafile Pdf vektoros grafikává van konvertálva, akkor a Pdf megtekintő eszközben előfordulhatnak teljesítményproblémák.

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
* osztály [`IPdfOptions`](/slides/python-net/hu/aspose.slides.export/ipdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)