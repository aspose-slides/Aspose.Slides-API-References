---
title: best_images_compression_ratio property
second_title: Aspose.Slides for Python via .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides.export/pdfoptions/best_images_compression_ratio/
weight: 60
---
## best_images_compression_ratio tulajdonság
Indicates if the most effective compression (instead of the default one) for each image must be selected 
            automatically. If set to **bool**.true, for every image in presentation the most appropriate compression 
            algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. 
            Best image compression ratio selection is computationally expensive and takes 
            an additional amount of RAM, and this option is **bool**.false by default.


### Megjegyzések

Default is **bool**.false.

### Definíció:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```


### Lásd még
* osztály [`PdfOptions`](/slides/python-net/hu/aspose.slides.export/pdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)