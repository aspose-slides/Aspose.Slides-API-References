---
title: add_clone method
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของคอลเลกชัน

### คืนค่า
สไลด์ใหม่



```python
def add_clone(self, source_slide):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่ต้องการทำสำเนา |


### หมายเหตุ
เมื่อทำการโคลนสไลด์ระหว่างการนำเสนอที่ต่างกัน master ของสไลด์อาจถูกโคลนด้วย  
Internal registry จะใช้เพื่อติดตาม master ที่ถูกโคลนอัตโนมัติเพื่อป้องกันการสร้างสำเนาซ้ำของ master slide เดียวกัน  
การโคลน master slide ด้วยตนเองจะไม่ถูกป้องกันหรือบันทึก  
หากคุณต้องการควบคุมกระบวนการโคลนมากขึ้นให้ใช้  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** หรือ  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** สำหรับการโคลนสไลด์,  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** หรือ  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** สำหรับการโคลนเลย์เอาต์และ  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** สำหรับการโคลน master


## add_clone(self, source_slide, section) {#islide-isection}
เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของส่วนที่ระบุ

### คืนค่า
สไลด์ใหม่



```python
def add_clone(self, source_slide, section):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่ต้องการทำสำเนา |
| section | [`ISection`](/slides/python-net/th/aspose.slides/isection) | ส่วนสำหรับสไลด์ใหม่ |


### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของคอลเลกชัน

### คืนค่า
สไลด์ใหม่



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่ต้องการทำสำเนา |
| dest_layout | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | เลย์เอาต์สไลด์สำหรับสไลด์ใหม่ |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุไปยังส่วนท้ายของคอลเลกชัน  
เลย์เอาต์ที่เหมาะสมจะถูกเลือกอัตโนมัติจาก master ที่ระบุ  
(เลย์เอาต์ที่เหมาะสมคือเลย์เอาต์ที่มี Type หรือ Name เท่ากับเลย์เอาต์ของสไลด์ต้นฉบับ) หากไม่มีเลย์เอาต์ที่เหมาะสม  
เลย์เอาต์ของสไลด์ต้นฉบับจะถูกโคลน (หาก allowCloneMissingLayout เป็น true) หรือจะเกิด PptxEditException (หาก allowCloneMissingLayout เป็น false)

### คืนค่า
สไลด์ใหม่



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่ต้องการทำสำเนา |
| dest_master | [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide) | master สไลด์สำหรับสไลด์ใหม่ |
| allow_clone_missing_layout | **bool** | หากไม่มีเลย์เอาต์ที่เหมาะสมใน master ที่ระบุแล้วเลย์เอาต์ของ <br/><br/>            สไลด์ต้นฉบับจะถูกโคลน (หาก allowCloneMissingLayout เป็น true) หรือ <br/><br/>            จะเกิด PptxEditException (หาก allowCloneMissingLayout เป็น false). |


### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | เกิดเมื่อไม่มีเลย์เอาต์ที่เหมาะสมใน master ที่ระบุและ <br/>            allowCloneMissingLayout เป็น false. |



### ดูเพิ่มเติม
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide)
* คลาส [`ISection`](/slides/python-net/th/aspose.slides/isection)
* คลาส [`ISlide`](/slides/python-net/th/aspose.slides/islide)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* คลาส [`SlideCollection`](/slides/python-net/th/aspose.slides/slidecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)