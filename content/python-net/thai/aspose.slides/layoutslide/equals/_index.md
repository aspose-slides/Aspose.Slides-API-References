---
title: equals method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/layoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
ระบุว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่.  
ค่าที่คืนจะคำนวณตามโครงสร้างของสไลด์และเนื้อหาคงที่.  
สองสไลด์เท่ากันหากรูปทรง, สไตล์, ข้อความ, การเคลื่อนไหวและการตั้งค่าอื่น ๆ เป็นต้น เท่ากัน การเปรียบเทียบจะไม่พิจารณาค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าปัจจุบันของวันที่ใน Date Placeholder.

### คืนค่า

**true**  หาก IBaseSlide ที่ระบุเท่ากับ IBaseSlide ปัจจุบัน;  
หากไม่เช่นนั้น, **false** .

```python
def equals(self, slide):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide) | IBaseSlide ที่จะเปรียบเทียบกับ IBaseSlide ปัจจุบัน. |

### ดูเพิ่ม
* คลาส [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide)
* คลาส [`LayoutSlide`](/slides/python-net/th/aspose.slides/layoutslide)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)