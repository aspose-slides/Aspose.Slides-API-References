---
title: jpeg_quality property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/ihtmloptions/jpeg_quality/
weight: 80
---
## jpeg_quality egenskap
Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet.
            Läs/skriv **int**.


### Anmärkningar

Har effekt endast när ett dokument innehåller JPEG-bilder.


Använd denna egenskap för att hämta eller ange kvaliteten på bilderna i ett dokument när du sparar i PDF-format.
            Värdet kan variera från 0 till 100 där 0 betyder sämst kvalitet men maximal komprimering och 100 betyder bästa kvalitet men minimal komprimering.


Standardvärdet är **95** .

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
* klass [`IHtmlOptions`](/slides/python-net/sv/aspose.slides.export/ihtmloptions)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)