---
title: add_clone method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
เพิ่มสำเนาของสไลด์เลย์เอาต์ที่ระบุไปยังงานนำเสนอ

### ผลลัพธ์

สไลด์ที่เพิ่ม



```python
def add_clone(self, source_layout):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | สไลด์ที่ต้องการโคลน |

### หมายเหตุ

เมื่อทำการโคลนเลย์เอาต์ระหว่างงานนำเสนอที่ต่างกัน มาสเตอร์ของเลย์เอาต์ก็สามารถถูกโคลนได้เช่นกัน
            เพื่อคงรูปแบบของแหล่งต้นทาง.
            การลงทะเบียนภายในจะถูกใช้เพื่อติดตามมาสเตอร์ที่ถูกโคลนอัตโนมัติเพื่อป้องกันไม่ให้สร้างสำเนาซ้ำของมาสเตอร์สไลด์เดียวกัน.
            การโคลนมาสเตอร์สไลด์ด้วยตนเองจะไม่ถูกป้องกันหรือบันทึกไว้.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
เพิ่มสำเนาของสไลด์เลย์เอาต์ที่ระบุไปยังงานนำเสนอ

### ผลลัพธ์

สไลด์ที่เพิ่ม



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | สไลด์ที่ต้องการโคลน |
| dest_master | [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับเลย์เอาต์ใหม่ |

### หมายเหตุ

1) เลย์เอาต์ใหม่จะถูกเชื่อมโยงกับมาสเตอร์ที่กำหนดในงานนำเสนอปลายทาง.
            ดังนั้นนี่เป็นการเทียบเท่ากับการคัดลอก/วางโดยใช้ตัวเลือก "Use Destination Theme" ใน PowerPoint.
            2) การเทียบเท่าของเมธอดนี้คือเมธอด **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide**
            ที่เข้าถึงด้วย [`IMasterSlide.layout_slides`](/slides/python-net/th/aspose.slides/imasterslide/layout_slides) คุณสมบัติ.



### ดูเพิ่มเติม
* คลาส [`GlobalLayoutSlideCollection`](/slides/python-net/th/aspose.slides/globallayoutslidecollection)
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)