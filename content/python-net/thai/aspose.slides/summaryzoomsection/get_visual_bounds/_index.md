---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### ผลลัพธ์

อ็อบเจกต์ [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตภาพของรูปร่าง
             ในพิกัดสไลด์.



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งกลับมานี้แสดงขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมด
             ที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพิกัดสไลด์

             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเชิงลบหากเนื้อหาที่เรนเดอร์ขยายเกินจุดกำเนิดของสไลด์

             ขอบเขตภาพคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์เช่น
             การแปลง (เช่น การหมุน), ความกว้างของเส้นและการเชื่อมต่อ,
             การจัดวางข้อความและการล้น, รูปร่าง SmartArt, และผลกระทบการจัดวางอื่น ๆ
             ที่มีผลต่อรูปลักษณ์ที่เรนเดอร์ขั้นสุดท้ายของรูปร่าง

             ขอบเขตที่ส่งกลับจะไม่ถูกคลิปให้เข้ากับสี่เหลี่ยมของสไลด์



### ดูเพิ่มเติม
* คลาส [`SummaryZoomSection`](/slides/python-net/th/aspose.slides/summaryzoomsection)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)