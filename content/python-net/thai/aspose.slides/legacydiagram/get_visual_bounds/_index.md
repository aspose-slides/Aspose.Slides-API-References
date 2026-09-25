---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### คืนค่า
อ็อบเจ็กต์ [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตภาพของรูปร่างในพิกัดสไลด์

```python
def get_visual_bounds(self):
    ...
```

### หมายเหตุ
สี่เหลี่ยมที่ส่งคืนแสดงขอบเขตที่จัดให้แนวแกนของเนื้อหาทั้งหมดที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพิกัดสไลด์

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีค่าพิกัดเป็นลบหากเนื้อหาที่เรนเดอร์ขยายออกนอกต้นจุดของสไลด์

ขอบเขตภาพคำนึงถึงด้านที่เกี่ยวกับการเรนเดอร์ เช่น การแปลง (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ, การวางข้อความและการล้น, รูปร่างของ SmartArt, และผลกระทบการจัดวางอื่น ๆ ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง

ขอบเขตที่ส่งคืนไม่ได้ถูกตัดให้เข้ากับสี่เหลี่ยมสไลด์

### ดูเพิ่มเติม
* คลาส [`LegacyDiagram`](/slides/python-net/th/aspose.slides/legacydiagram)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)