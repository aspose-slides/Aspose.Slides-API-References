---
title: best_images_compression_ratio property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/ipdfoptions/best_images_compression_ratio/
weight: 50
---
## best_images_compression_ratio egenskap
Anger om den mest effektiva komprimeringen (i stället för standardkomprimeringen) för varje bild ska väljas automatiskt. Om den sätts till **bool**.true, kommer den mest lämpliga komprimeringsalgoritmen att väljas för varje bild i presentationen, vilket leder till en mindre storlek på det resulterande PDF-dokumentet. Val av den bästa bildkomprimeringsförhållandet är beräkningsmässigt krävande och kräver extra RAM, och detta alternativ är som standard **bool**.false.


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
* klass [`IPdfOptions`](/slides/python-net/sv/aspose.slides.export/ipdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)