---
title: find_shape method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: ค้นหา shape โดยใช้ข้อความแทนที่ในพรีเซนเทชันหรือสไลด์
type: docs
url: /th/aspose.slides.util/slideutil/find_shape/
weight: 30
---
## find_shape(pres, alt_text) {#ipresentation-str}
ค้นหา shape โดยข้อความแทนที่ในพรีเซนเทชัน PPTX

### คืนค่า

Shape หรือ None.



```python
@staticmethod
def find_shape(pres, alt_text):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| pres | [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation) | พรีเซนเทชันที่สแกน |
| alt_text | **str** | ข้อความแทนที่ของ shape |


## find_shape(slide, alt_text) {#ibaseslide-str}
ค้นหา shape โดยข้อความแทนที่บนสไลด์ในพรีเซนเทชัน PPTX

### คืนค่า

Shape หรือ None.



```python
@staticmethod
def find_shape(slide, alt_text):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide) | สไลด์ที่สแกน |
| alt_text | **str** | ข้อความแทนที่ของ shape |



### ดูเพิ่มเติม
* คลาส [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide)
* คลาส [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation)
* คลาส [`IShape`](/slides/python-net/th/aspose.slides/ishape)
* คลาส [`SlideUtil`](/slides/python-net/th/aspose.slides.util/slideutil)
* โมดูล [`aspose.slides.util`](/slides/python-net/th/aspose.slides.util)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)