---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### คืนค่า

อ็อบเจกต์ **aspose.slides.RectangleF** ที่แสดงขอบเขตภาพของรูปร่างในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งกลับแสดงขอบเขตที่เรียงตามแกนของเนื้อหาทั้งหมดที่รูปสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดของสไลด์

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูป ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยายออกนอกจุดกำเนิดของสไลด์

ขอบเขตภาพพิจารณาถึงแง่มุมที่เกี่ยวกับการเรนเดอร์ เช่น การแปลง (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ, การจัดรูปแบบข้อความและการล้น, รูปร่างของ SmartArt, และผลกระทบการจัดวางอื่น ๆ ที่มีผลต่อรูปแบบที่แสดงผลสุดท้ายของรูปร่าง

ขอบเขตที่ส่งกลับไม่ได้ถูกคลิปให้ตรงกับสี่เหลี่ยมสไลด์

### ดูเพิ่มเติม
* คลาส [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)