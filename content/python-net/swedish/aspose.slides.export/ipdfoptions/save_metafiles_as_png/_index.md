---
title: save_metafiles_as_png property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png egenskap
Sant för att konvertera alla metafiler som används i en presentation till PNG-bilder.
            Läs/skriv **bool**.

### Anmärkningar

Standard är **true** .
            Pdf-dokument kan innehålla vektorgrafik och rasterbilder. 
            Om SaveMetafilesAsPng är satt till true konverteras käll-Metafile-bilden till Png-format och sparas i Pdf som en rasterbild. Om SaveMetafilesAsPng är satt till false konverteras käll-Metafile till Pdf-vektorgrafik. Varje tillvägagångssätt har fördelar och nackdelar. Till exempel, om Metafile konverteras till PNG, kan viss kvalitetsförlust uppstå vid skalning av det resulterande dokumentet. Om Metafile konverteras till Pdf-vektorgrafik, kan prestandaproblem i Pdf-visningsverktyg uppkomma.

### Definition:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### Se även
* klass [`IPdfOptions`](/slides/python-net/sv/aspose.slides.export/ipdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)