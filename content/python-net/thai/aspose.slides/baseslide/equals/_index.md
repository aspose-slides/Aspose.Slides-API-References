---
title: equals method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/baseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
กำหนดว่าตัวอย่างสอง IBaseSlide เท่าเทียมกันหรือไม่.
ค่าที่คืนถูกคำนวณตามโครงสร้างของสไลด์และเนื้อหาคงที่.
สองสไลด์เท่ากันหากรูปทรง, สไตล์, ข้อความ, การเคลื่อนไหวและการตั้งค่าอื่นๆ เป็นต้น ทั้งหมดเท่ากัน การเปรียบเทียบจะไม่พิจารณาค่าตัวระบุเฉพาะ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าที่เป็นวันที่ปัจจุบันใน Date Placeholder.

### Returns

**true** หาก IBaseSlide ที่ระบุเท่ากับ IBaseSlide ปัจจุบัน; มิฉะนั้น **false** .

```python
def equals(self, slide):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide) | The IBaseSlide to compare with the current IBaseSlide. |

### ดูเพิ่มเติม
* คลาส [`BaseSlide`](/slides/python-net/th/aspose.slides/baseslide)
* คลาส [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)