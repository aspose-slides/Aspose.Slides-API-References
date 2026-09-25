---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
ดึงขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### คืนค่า

เป็น [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตภาพของรูปร่าง
             ในพิกัดสไลด์.

```python
def get_visual_bounds(self):
    ...
```

### หมายเหตุ

สี่เหลี่ยมที่ส่งคืนแสดงขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมด
             ที่รูปทรงสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์.

             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปทรง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเป็นค่าติดลบหากเนื้อหาที่เรนเดอร์ขยายออกไปนอกตำแหน่งต้นของสไลด์.

             ขอบเขตภาพจะพิจารณาปัจจัยที่เกี่ยวข้องกับการเรนเดอร์ เช่น
             การแปลง (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ,
             การจัดวางข้อความและการล้น, รูปร่าง SmartArt, และผลลัพธ์การจัดวางอื่น ๆ
             ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปทรง.

             ขอบเขตที่ส่งคืนไม่ได้ถูกคลิปให้เข้ากับสี่เหลี่ยมสไลด์.

### ดูเพิ่มเติม
* คลาส [`InkActions`](/slides/python-net/th/aspose.slides.ink/inkactions)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides.ink`](/slides/python-net/th/aspose.slides.ink)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)