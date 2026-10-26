---
title: best_images_compression_ratio property
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides.export/pdfoptions/best_images_compression_ratio/
weight: 60
---
## best_images_compression_ratio คุณสมบัติ
Indicates if the most effective compression (instead of the default one) for each image must be selected 
            automatically. If set to **bool**.true, for every image in presentation the most appropriate compression 
            algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. 
            Best image compression ratio selection is computationally expensive and takes 
            an additional amount of RAM, and this option is **bool**.false by default.


### หมายเหตุ

ค่าเริ่มต้นคือ **bool**.false.

### คำนิยาม:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```


### ดูเพิ่มเติม
* คลาส [`PdfOptions`](/slides/python-net/th/aspose.slides.export/pdfoptions)
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)