---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
รับขอบเขตเชิงภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### คืนค่า

A **aspose.slides.RectangleF** ที่เป็นสี่เหลี่ยมที่แสดงขอบเขตเชิงภาพของรูปร่างในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งคืนแสดงขอบเขตที่จัดแนวนามแกนของเนื้อหาทั้งหมดที่รูปสร้างขึ้นระหว่างการเรนเดอร์ในพิกัดสไลด์

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีพิกัดเป็นค่าติดลบหากเนื้อหาที่เรนเดอร์ขยายเกินตำแหน่งต้นของสไลด์

ขอบเขตเชิงภาพคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์ เช่น การแปลง (เช่น การหมุน), ความกว้างของขอบและการเชื่อมต่อ, การจัดวางข้อความและการล้น, เรขาคณิต SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง

ขอบเขตที่ส่งคืนไม่ได้ถูกตัดให้พอดีกับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`Connector`](/slides/python-net/th/aspose.slides/connector)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)