---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตเชิงภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### คืนค่า

A [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตเชิงภาพของรูปร่าง
             ในพิกัดสไลด์.



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมผืนฝังที่ส่งคืนแสดงขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมด
             ที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์.
             
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเชิงลบหากเนื้อหาที่เรนเดอร์ขยายออกไป
             เกินจุดเริ่มต้นของสไลด์.
             
             ขอบเขตเชิงภาพจะคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์เช่น
             การแปลง (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ,
             การจัดวางข้อความและการล้น, เรขาคณิต SmartArt, และผลกระทบการจัดวางอื่นๆ
             ที่ส่งผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง.
             
             ขอบเขตที่ส่งคืนจะไม่ถูกคลิปให้เข้ากับสี่เหลี่ยมสไลด์.



### ดูเพิ่มเติม
* คลาส [`ZoomObject`](/slides/python-net/th/aspose.slides/zoomobject)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)