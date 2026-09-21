---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### Returns

A **aspose.slides.RectangleF** ที่แสดงขอบเขตภาพของรูปร่างในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### Remarks

สี่เหลี่ยมที่ส่งกลับแสดงขอบเขตที่ตั้งแนวแกนของเนื้อหาทั้งหมดที่รูปร่างสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์  
             
These bounds may differ from the shape's model bounds
([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
และอาจมีพิกัดเชิงลบหากเนื้อหาที่เรนเดอร์ขยายออกไปเกินต้นจุดของสไลด์  
             
ขอบเขตภาพพิจารณาปัจจัยที่เกี่ยวกับการเรนเดอร์เช่นการแปลง (เช่น การหมุน), ความกว้างของเส้นและการเชื่อมต่อ, การจัดวางข้อความและการล้น, รูปร่างของ SmartArt, และผลกระทบการจัดวางอื่น ๆ ที่ส่งผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง  
             
ขอบเขตที่ส่งกลับไม่ได้ถูกคลิปให้เข้ากับสี่เหลี่ยมสไลด์



### See Also
* คลาส [`Ink`](/slides/python-net/th/aspose.slides.ink/ink)
* โมดูล [`aspose.slides.ink`](/slides/python-net/th/aspose.slides.ink)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)