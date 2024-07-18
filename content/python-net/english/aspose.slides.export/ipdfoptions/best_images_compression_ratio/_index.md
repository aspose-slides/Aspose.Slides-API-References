---
title: best_images_compression_ratio property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/ipdfoptions/best_images_compression_ratio/
weight: 50
---


## best_images_compression_ratio property
Indicates if the most effective compression (instead of the default one) for each image must be selected 
            automatically. If set to **bool**.true, for every image in presentation the most appropriate compression 
            algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. 
            Best image compression ratio selection is computationally expensive and takes 
            an additional amount of RAM, and this option is **bool**.false by default.


### Remarks

Default is **bool**.false.

### Definition:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```


### See Also
* class [`IPdfOptions`](/slides/python-net/aspose.slides.export/ipdfoptions)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

