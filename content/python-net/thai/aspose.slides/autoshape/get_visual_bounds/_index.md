---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### คืนค่า

อ็อบเจกต์ **aspose.slides.RectangleF** ที่แสดงขอบเขตภาพของรูปร่างในระบบพิกัดของสไลด์
             
```python
def get_visual_bounds(self):
    ...
```

### หมายเหตุ

สี่เหลี่ยมที่ส่งกลับแสดงขอบเขตเรียงตามแกนของเนื้อหาทั้งหมด
             ที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพื้นที่พิกัดของสไลด์.
             
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             
             และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยายออก
             นอกจุดกำเนิดของสไลด์.
             
             ขอบเขตภาพคำนึงถึงแง่มุมที่เกี่ยวข้องกับการเรนเดอร์เช่น
             การแปลง (เช่น การหมุน), ความกว้างและการเชื่อมต่อของเส้น,
             การจัดวางข้อความและการล้น, รูปทรงของ SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ
             ที่มีผลต่อรูปลักษณ์สุดท้ายของรูปร่างที่เรนเดอร์.
             
             ขอบเขตที่ส่งกลับจะไม่ถูกคลิปให้ตรงกับสี่เหลี่ยมสไลด์.

### ดูเพิ่มเติม
* คลาส [`AutoShape`](/slides/python-net/th/aspose.slides/autoshape)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)