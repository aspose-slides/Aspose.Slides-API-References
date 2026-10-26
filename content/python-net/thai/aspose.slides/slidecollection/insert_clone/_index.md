---
title: insert_clone method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
แทรกสำเนาของสไลด์ที่กำหนดลงในตำแหน่งที่ระบุของคอลเลกชัน

### ผลลัพธ์

สไลด์ที่ถูกแทรก



```python
def insert_clone(self, index, source_slide):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีของสไลด์ใหม่. |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่ต้องทำสำเนา. |

### หมายเหตุ

เมื่อทำการคัดลอกสไลด์ระหว่างการนำเสนอที่ต่างกัน มาสเตอร์ของสไลด์อาจถูกคัดลอกด้วยเช่นกัน.  
ทะเบียนภายในถูกใช้เพื่อติดตามมาสเตอร์ที่ถูกคัดลอกโดยอัตโนมัติ เพื่อป้องกันการสร้างสำเนาซ้ำของมาสเตอร์สไลด์เดียวกัน.  
การคัดลอกมาสเตอร์สไลด์ด้วยตนเองจะไม่ถูกป้องกันหรือบันทึกไว้.  
หากคุณต้องการควบคุมกระบวนการคัดลอกเพิ่มเติมให้ใช้  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** หรือ  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** สำหรับการคัดลอกสไลด์และ  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** สำหรับการคัดลอกมาสเตอร์.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
แทรกสำเนาของสไลด์ที่กำหนดลงในตำแหน่งที่ระบุของคอลเลกชัน

### ผลลัพธ์

สไลด์ที่ถูกแทรก



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีของสไลด์ใหม่. |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่ต้องทำสำเนา. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | สไลด์เลย์เอาต์สำหรับสไลด์ใหม่. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
แทรกสำเนาของสไลด์ต้นทางที่ระบุลงในตำแหน่งที่ระบุของคอลเลกชัน.  
เลย์เอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจากมาสเตอร์ที่ระบุ (เลย์เอาต์ที่เหมาะสมคือเลย์เอาต์ที่มี Type หรือ Name เหมือนกับเลย์เอาต์ของสไลด์ต้นทาง). หากไม่มีเลย์เอาต์ที่เหมาะสม เลย์เอาต์ของสไลด์ต้นทางจะถูกคัดลอก (หาก allowCloneMissingLayout เป็น true) หรือจะเกิดข้อยกเว้น PptxEditException (หาก allowCloneMissingLayout เป็น false).

### ผลลัพธ์

สไลด์ที่ถูกแทรก



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีของสไลด์ใหม่. |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่ต้องทำสำเนา. |
| dest_master | [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับสไลด์ใหม่. |
| allow_clone_missing_layout | **bool** | หากไม่มีเลย์เอาต์ที่เหมาะสมในมาสเตอร์ที่ระบุแล้วเลย์เอาต์ของ <br/><br/>            สไลด์ต้นทางจะถูกคัดลอก (หาก allowCloneMissingLayout เป็น true) หรือ <br/><br/>            PptxEditException จะถูกโยน (หาก allowCloneMissingLayout เป็น false). |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | ถูกโยนเมื่อไม่มีเลย์เอาต์ที่เหมาะสมในมาสเตอร์ที่ระบุและ <br/>            allowCloneMissingLayout เป็น false. |



### ดูเพิ่มเติม
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide)
* คลาส [`ISlide`](/slides/python-net/th/aspose.slides/islide)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* คลาส [`SlideCollection`](/slides/python-net/th/aspose.slides/slidecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)