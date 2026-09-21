---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### คืนค่า

A **aspose.slides.RectangleF** ที่แสดงขอบเขตภาพของรูปร่างในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่คืนค่ามาแสดงขอบเขตแบบขนานแกนของเนื้อหาทั้งหมดที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์

เหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีพิกัดเป็นลบหากเนื้อหาที่เรนเดอร์ขยายออกนอกจุดกำเนิดของสไลด์

ขอบเขตภาพพิจารณาปัจจัยที่เกี่ยวข้องกับการเรนเดอร์ เช่น การแปลง (เช่น การหมุน), ความกว้างของเส้นและการเชื่อมต่อ, การจัดวางข้อความและการล้น, รูปร่าง SmartArt, และผลกระทบการจัดวางอื่น ๆ ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง

ขอบเขตที่คืนค่าไม่ได้ถูกคลิปให้ตรงกับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`ZoomObject`](/slides/python-net/th/aspose.slides/zoomobject)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)