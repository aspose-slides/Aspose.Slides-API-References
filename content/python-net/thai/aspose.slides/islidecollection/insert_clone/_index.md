---
title: insert_clone method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน

### คืนค่า
สไลด์ที่แทรก

```python
def insert_clone(self, index, source_slide):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีของสไลด์ใหม่. |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่จะทำสำเนา. |

### หมายเหตุ
เมื่อทำสำเนาสไลด์ระหว่างงานนำเสนอที่แตกต่างกัน มาสเตอร์ของสไลด์อาจถูกทำสำเนาไปด้วย
            ระบบทะเบียนภายในถูกใช้เพื่อจับตามมาสเตอร์ที่ถูกทำสำเนาโดยอัตโนมัติเพื่อป้องกันการสร้างสำเนาซ้ำของมาสเตอร์สไลด์เดียวกัน
            การทำสำเนามาสเตอร์สไลด์ด้วยมือจะไม่ถูกป้องกันหรือบันทึกไว้
            หากคุณต้องการควบคุมกระบวนการทำสำเนาเพิ่มเติม ให้ใช้
            **Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** หรือ
            **Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** สำหรับการทำสำเนาสไลด์และ
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** สำหรับการทำสำเนามาสเตอร์

## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน

### คืนค่า
สไลด์ที่แทรก

```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีของสไลด์ใหม่. |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่จะทำสำเนา. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | เลย์เอาต์สไลด์สำหรับสไลด์ใหม่. |

## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
แทรกสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน
            เลย์เอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจากมาสเตอร์ที่ระบุ
            (เลย์เอาต์ที่เหมาะสมคือเลย์เอาต์ที่มี Type หรือ Name เท่ากับของเลย์เอาต์ของสไลด์ต้นฉบับ). หากไม่มีเลย์เอาต์ที่เหมาะสม
            เลย์เอาต์ของสไลด์ต้นฉบับจะถูกทำสำเนา (หาก allowCloneMissingLayout เป็นจริง) หรือจะทำให้เกิด PptxEditException (หาก allowCloneMissingLayout
            เป็นเท็จ)

### คืนค่า
สไลด์ที่แทรก

```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีของสไลด์ใหม่. |
| source_slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | สไลด์ที่จะทำสำเนา. |
| dest_master | [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับสไลด์ใหม่. |
| allow_clone_missing_layout | **bool** | หากไม่มีเลย์เอาต์ที่เหมาะสมในมาสเตอร์ที่ระบุแล้ว เลย์เอาต์ของ <br/><br/>            source slide จะถูกทำสำเนา (หาก allowCloneMissingLayout เป็นจริง) หรือ <br/><br/>            PptxEditException จะถูกโยน (หาก allowCloneMissingLayout เป็นเท็จ). |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | ถูกโยนเมื่อไม่มีเลย์เอาต์ที่เหมาะสมในมาสเตอร์ที่ระบุและ <br/>            allowCloneMissingLayout เป็นเท็จ. |

### ดูเพิ่มเติม
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide)
* คลาส [`ISlide`](/slides/python-net/th/aspose.slides/islide)
* คลาส [`ISlideCollection`](/slides/python-net/th/aspose.slides/islidecollection)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)