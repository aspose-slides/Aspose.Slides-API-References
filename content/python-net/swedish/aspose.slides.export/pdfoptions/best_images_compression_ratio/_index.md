---
title: best_images_compression_ratio property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/pdfoptions/best_images_compression_ratio/
weight: 60
---
## best_images_compression_ratio egenskap
Indikerar om den mest effektiva komprimeringen (istället för den förvalda) för varje bild måste väljas 
            automatiskt. Om den är inställd på **bool**.true, för varje bild i presentationen kommer den mest lämpliga komprimeringsalgoritmen att 
            väljas, vilket kommer att leda till en mindre storlek på det resulterande PDF-dokumentet. 
            Val av bästa bildkomprimeringsförhållande är beräkningsmässigt dyrt och tar 
            en extra mängd RAM, och detta alternativ är **bool**.false som standard.


### Anmärkningar

Standard är **bool**.false.

### Definition:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```


### Se även
* klass [`PdfOptions`](/slides/python-net/sv/aspose.slides.export/pdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)