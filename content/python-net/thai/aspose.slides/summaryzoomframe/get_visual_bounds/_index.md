---
title: get_visual_bounds method
second_title: อ้างอิง API Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับค่าขอบเขตเชิงภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### ผลลัพธ์
A [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่เป็นตัวแทนของขอบเขตเชิงภาพของรูปร่างในพิกัดสไลด์

```python
def get_visual_bounds(self):
    ...
```

### หมายเหตุ
สี่เหลี่ยมที่ส่งคืนแสดงขอบเขตที่จัดตามแกนของเนื้อหาทั้งหมดที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพิกัดสไลด์  
ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง  
([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))  
และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยายออกไปเกินจุดกำเนิดของสไลด์  
ขอบเขตเชิงภาพคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์ เช่น การแปลง (เช่น การหมุน) ความกว้างของเส้นขอบและการเชื่อมต่อ การจัดวางข้อความและการล้น, รูปทรง SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง  
ขอบเขตที่ส่งคืนไม่ได้ถูกคลิปให้ตรงกับสี่เหลี่ยมสไลด์

### ดูเพิ่มเติม
* class [`SummaryZoomFrame`](/slides/python-net/th/aspose.slides/summaryzoomframe)
* class [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)