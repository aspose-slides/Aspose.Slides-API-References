---
title: best_images_compression_ratio property
second_title: Aspose.Slides 用於 Python 的 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/ipdfoptions/best_images_compression_ratio/
weight: 50
---
## best_images_compression_ratio 屬性
Indicates if the most effective compression (instead of the default one) for each image must be selected 
            automatically. If set to **bool**.true, for every image in presentation the most appropriate compression 
            algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. 
            Best image compression ratio selection is computationally expensive and takes 
            an additional amount of RAM, and this option is **bool**.false by default.

### 備註

Default is **bool**.false.

### 定義:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```

### 另請參閱
* 類別 [`IPdfOptions`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)