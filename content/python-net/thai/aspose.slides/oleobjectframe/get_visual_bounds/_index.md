---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### คืนค่า

อ็อบเจกต์ **aspose.slides.RectangleF** ที่แสดงขอบเขตภาพของรูปร่าง
             ในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งคืนแสดงขอบเขตที่จัดแนวแกนของเนื้อหาทั้งหมดที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพื้นที่พิกัดของสไลด์
             
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตของโมเดลรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเชิงลบหากเนื้อหาที่เรนเดอร์ขยายออกไป
             เกินจุดกำเนิดของสไลด์
             
             ขอบเขตภาพคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์เช่น
             การแปลง (เช่น การหมุน), ความกว้างของเส้นขีดและการเชื่อมต่อ,
             การจัดรูปแบบข้อความและการล้น, เรขาคณิตของ SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ
             ที่ส่งผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง
             
             ขอบเขตที่ส่งคืนไม่ได้ถูกตัดคลิปให้ตรงกับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`OleObjectFrame`](/slides/python-net/th/aspose.slides/oleobjectframe)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)