---
title: save_metafiles_as_png property
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png property
True pro konverzi všech metafiles použitých v prezentaci na obrázky PNG.
            Read/write **bool**.


### Poznámky

Výchozí hodnota je **true** .
            Dokument Pdf může obsahovat vektorovou grafiku a rastrové obrázky. 
            Pokud je SaveMetafilesAsPng nastaveno na true, pak je zdrojový Metafile 
            obrázek převeden do formátu Png a uložen do Pdf jako rastrový 
            obrázek. Pokud je SaveMetafilesAsPng nastaveno na false, pak je zdrojový Metafile 
            převeden na vektorovou grafiku Pdf. Každý přístup má výhody 
            i nevýhody. Například, pokud je Metafile převeden na PNG, 
            pak je možné, že během škálování výsledného 
            dokumentu dojde ke ztrátě kvality. Pokud je Metafile převeden na vektorovou grafiku Pdf, 
            pak mohou nastat výkonnostní problémy v nástroji pro prohlížení Pdf.

### Definice:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```


### Viz také
* třída [`IPdfOptions`](/slides/python-net/cs/aspose.slides.export/ipdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)