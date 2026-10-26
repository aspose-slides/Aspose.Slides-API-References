---
title: jpeg_quality property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/ipdfoptions/jpeg_quality/
weight: 150
---
## jpeg_quality egenskap
Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet.
            Läs/skriv **int**.


### Anmärkningar

Har endast effekt när ett dokument innehåller JPEG-bilder.


Använd den här egenskapen för att hämta eller ange kvaliteten på bilderna i ett dokument när du sparar i PDF-format.
            Värdet kan variera från 0 till 100 där 0 betyder sämst kvalitet men maximal kompression och 100 betyder bästa kvalitet men minimal kompression.


Standardvärdet är **100** .

### Definition:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### Se även
* klass [`IPdfOptions`](/slides/python-net/sv/aspose.slides.export/ipdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)