---
title: jpeg_quality property
second_title: Aspose.Slides dla Pythona via .NET Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.export/ipdfoptions/jpeg_quality/
weight: 150
---
## właściwość jpeg_quality
Returns or sets a value determining the quality of the JPEG images inside PDF document.
            Odczyt/zapis **int**.


### Uwagi

Has effect only when a document contains JPEG images.


Use this property to get or set the quality of the images inside a document when saving in PDF format.
            The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.


The default value is **100** .

### Definicja:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### Zobacz także
* klasa [`IPdfOptions`](/slides/python-net/pl/aspose.slides.export/ipdfoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)