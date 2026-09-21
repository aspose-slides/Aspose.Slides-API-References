---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### คืนค่า

วัตถุ **aspose.slides.RectangleF** ที่แสดงขอบเขตภาพของรูปทรงในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งกลับแสดงขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมดที่สร้างโดยรูปทรงระหว่างการเรนเดอร์ในพิกัดสไลด์  

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปทรง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยายออกไปเกินจุดกำเนิดของสไลด์  

ขอบเขตภาพคำนึงถึงแง่มุมที่เกี่ยวข้องกับการเรนเดอร์เช่น การแปลง (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ, การจัดวางข้อความและการล้น, SmartArt geometry, และผลกระทบการจัดวางอื่น ๆ ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปทรง  

ขอบเขตที่ส่งกลับจะไม่ถูกตัดให้เข้าสู่สี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`GroupShape`](/slides/python-net/th/aspose.slides/groupshape)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)