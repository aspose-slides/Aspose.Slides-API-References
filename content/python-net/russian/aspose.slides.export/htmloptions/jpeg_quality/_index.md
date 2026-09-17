---
title: jpeg_quality property
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.export/htmloptions/jpeg_quality/
weight: 90
---
## jpeg_quality свойство
Returns or sets a value determining the quality of the JPEG images inside PDF document.
            Чтение/запись **int**.


### Примечания

Has effect only when a document contains JPEG images.


Use this property to get or set the quality of the images inside a document when saving in PDF format.
            The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.


The default value is **95** .

### Определение:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### См. также
* класс [`HtmlOptions`](/slides/python-net/ru/aspose.slides.export/htmloptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)