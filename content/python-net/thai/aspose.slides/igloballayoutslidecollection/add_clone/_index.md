---
title: add_clone method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/igloballayoutslidecollection/add_clone/
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
| source_layout | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | สไลด์ที่จะคัดลอก |

### หมายเหตุ

เมื่อทำการคัดลอกเลย์เอาต์ระหว่างงานนำเสนอที่ต่างกัน มาสเตอร์ของเลย์เอาต์อาจถูกคัดลอกด้วยเพื่อคงรูปแบบของต้นฉบับ
ใช้รีจิสทรีภายในเพื่อติดตามมาสเตอร์ที่ถูกคัดลอกอัตโนมัติ เพื่อป้องกันการสร้างสำเนาหลายสำเนาของสไลด์มาสเตอร์เดียวกัน
การคัดลอกมาสเตอร์สไลด์ด้วยตนเองจะไม่ถูกป้องกันหรือบันทึก



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
| source_layout | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | สไลด์ที่จะคัดลอก |
| dest_master | [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide) | สไลด์แม่สำหรับเลย์เอาต์ใหม่ |

### หมายเหตุ

เลย์เอาต์ใหม่จะถูกเชื่อมโยงกับมาสเตอร์ที่กำหนดไว้ในงานนำเสนอปลายทาง
ดังนั้นนี่คือการทำงานที่คล้ายกับการคัดลอก/วางพร้อมตัวเลือก "Use Destination Theme" ใน PowerPoint



### ดูเพิ่มเติม
* คลาส [`IGlobalLayoutSlideCollection`](/slides/python-net/th/aspose.slides/igloballayoutslidecollection)
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)