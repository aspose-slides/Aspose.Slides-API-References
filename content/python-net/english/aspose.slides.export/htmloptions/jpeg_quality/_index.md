---
title: jpeg_quality property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/htmloptions/jpeg_quality/
weight: 70
---


## jpeg_quality property
Returns or sets a value determining the quality of the JPEG images inside PDF document.
            Read/write .NET type System.Byte.


### Remarks

Has effect only when a document contains JPEG images.


Use this property to get or set the quality of the images inside a document when saving in PDF format.
            The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.


The default value is **95** .

### Definition:
```python
@property
def jpeg_quality(self):
    ...
@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```
