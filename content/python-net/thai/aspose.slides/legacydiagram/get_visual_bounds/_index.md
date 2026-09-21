---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
รับค่าขอบเขตที่มองเห็นของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### คืนค่า
วัตถุ **aspose.slides.RectangleF** ที่แสดงขอบเขตที่มองเห็นของรูปทรงในพิกัดสไลด์

```python
def get_visual_bounds(self):
    ...
```

### หมายเหตุ
สี่เหลี่ยมที่ส่งกลับแสดงขอบเขตที่จัดแนวแกนของเนื้อหาทั้งหมดที่รูปทรงสร้างขึ้นระหว่างการเรนเดอร์ในพิกัดสไลด์

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตแบบจำลองของรูปทรง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยายเกินจุดกำเนิดของสไลด์

ขอบเขตที่มองเห็นคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์เช่น การแปลง (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ, การจัดตำแหน่งข้อความและการล้น, รูปร่าง SmartArt, และผลกระทบการจัดวางอื่น ๆ ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปทรง

ขอบเขตที่ส่งกลับจะไม่ถูกตัดคลิปให้เข้ากับสี่เหลี่ยมสไลด์

### ดูเพิ่มเติม
* คลาส [`LegacyDiagram`](/slides/python-net/th/aspose.slides/legacydiagram)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)