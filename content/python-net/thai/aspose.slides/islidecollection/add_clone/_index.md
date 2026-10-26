---
title: add_clone method
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
เพิ่มสำเนาของสไลด์ที่ระบุลงที่ตำแหน่งท้ายของคอลเลกชัน

### ผลลัพธ์

สไลด์ใหม่



```python
def add_clone(self, source_slide):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่ต้องการโคลน |

### หมายเหตุ

เมื่อทำการโคลนสไลด์ระหว่างการนำเสนอที่แตกต่างกัน มาสเตอร์ของสไลด์อาจถูกโคลนด้วย
Internal registry is used to track automatically cloned masters to prevent creation of 
multiple clones of the same master slide.
Manual cloning of master slides will be neither prevented nor registered.
If you need more control over cloning process use
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** or
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides,
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** or
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** for cloning layouts and
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.


## add_clone(self, source_slide, section) {#islide-isection}
เพิ่มสำเนาของสไลด์ที่ระบุลงที่ตำแหน่งท้ายของส่วนที่ระบุ

### ผลลัพธ์

สไลด์ใหม่



```python
def add_clone(self, source_slide, section):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่ต้องการโคลน |
| section | [`ISection`](/slides/python-net/th/aspose.slides/isection) | ส่วนสำหรับสไลด์ใหม่ |

### Exceptions
| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
เพิ่มสำเนาของสไลด์ที่ระบุลงที่ตำแหน่งท้ายของคอลเลกชัน

### ผลลัพธ์

สไลด์ใหม่



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่ต้องการโคลน |
| dest_layout | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | เลย์เอาต์สไลด์สำหรับสไลด์ใหม่ |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุลงที่ตำแหน่งท้ายของคอลเลกชัน
เลย์เอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจากมาสเตอร์ที่ระบุ (เลย์เอาต์ที่เหมาะสมคือเลย์เอาต์ที่มี Type หรือ Name ตรงกับเลย์เอาต์ของสไลด์ต้นฉบับ) หากไม่มีเลย์เอาต์ที่เหมาะสม เลย์เอาต์ของสไลด์ต้นฉบับจะถูกโคลน (หาก allowCloneMissingLayout เป็น true) หรือจะเกิด PptxEditException (หาก allowCloneMissingLayout เป็น false)

### ผลลัพธ์

สไลด์ใหม่



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่ต้องการโคลน |
| dest_master | [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับสไลด์ใหม่ |
| allow_clone_missing_layout | **bool** | หากไม่มีเลย์เอาต์ที่เหมาะสมในมาสเตอร์ที่ระบุ เลย์เอาต์ของ<br/><br/>สไลด์ต้นฉบับจะถูกโคลน (หาก allowCloneMissingLayout เป็น true) หรือ<br/><br/>PptxEditException จะถูกโยน (หาก allowCloneMissingLayout เป็น false) |

### Exceptions
| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | Thrown if there is no appropriate layout in specified master and <br/>            allowCloneMissingLayout is false. |



### ดูเพิ่มเติม
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide)
* คลาส [`ISection`](/slides/python-net/th/aspose.slides/isection)
* คลาส [`ISlide`](/slides/python-net/th/aspose.slides/islide)
* คลาส [`ISlideCollection`](/slides/python-net/th/aspose.slides/islidecollection)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)