---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตเชิงภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### ผลลัพธ์

[`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตเชิงภาพของรูปร่างในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งคืนแสดงขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมดที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพิกัดสไลด์

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีค่าพิกัดเป็นลบหากเนื้อหาที่เรนเดอร์ขยายเกินจุดเริ่มต้นของสไลด์

ขอบเขตเชิงภาพคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์ เช่น การแปลงรูป (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ, การจัดวางข้อความและการล้น, รูปทรง SmartArt, และผลกระทบการจัดวางอื่น ๆ ที่ส่งผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง

ขอบเขตที่ส่งคืนไม่ถูกตัดให้เข้ากับสี่เหลี่ยมสไลด์



### ดูเพิ่ม
* คลาส [`GroupShape`](/slides/python-net/th/aspose.slides/groupshape)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)