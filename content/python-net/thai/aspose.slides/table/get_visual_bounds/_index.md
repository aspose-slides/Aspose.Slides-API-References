---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### คืนค่า

อ็อบเจกต์ [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตภาพของรูปร่างในพิกัดสไลด์

```python
def get_visual_bounds(self):
    ...
```

### หมายเหตุ
สี่เหลี่ยมที่ส่งกลับแสดงขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมด  
ที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพื้นที่พิกัดของสไลด์

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง  
([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))  
และอาจมีพิกัดที่เป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยายออกไป  
เกินจุดเริ่มต้นของสไลด์

ขอบเขตภาพคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์ เช่น  
การแปลง (เช่น การหมุน), ความกว้างของเส้นและการเชื่อมต่อ,  
การจัดวางข้อความและการล้น, รูปทรง SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ  
ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง

ขอบเขตที่ส่งกลับไม่ถูกตัดให้เข้ากับสี่เหลี่ยมของสไลด์

### ดูเพิ่มเติม
* คลาส [`Table`](/slides/python-net/th/aspose.slides/table)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)