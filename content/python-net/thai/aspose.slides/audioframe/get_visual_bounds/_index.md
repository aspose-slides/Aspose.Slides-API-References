---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API เอกสารอ้างอิง
description: 
type: docs
url: /th/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### ค่าที่ส่งคืน
อ็อบเจกต์ [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตภาพของรูปร่างในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ
สี่เหลี่ยมที่ส่งคืนแสดงขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมด
             ที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์
ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเป็นค่าติดลบหากเนื้อหาที่เรนเดอร์ขยายออก
             เกินจุดเริ่มต้นของสไลด์
ขอบเขตภาพพิจารณาปัจจัยที่เกี่ยวข้องกับการเรนเดอร์เช่น
             การแปลง (เช่น การหมุน), ความกว้างของเส้นและการเชื่อมต่อ,
             การจัดวางข้อความและการล้น, รูปร่าง SmartArt, และผลกระทบการจัดวางอื่น ๆ
             ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง
ขอบเขตที่ส่งคืนจะไม่ถูกตัดให้ตรงกับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`AudioFrame`](/slides/python-net/th/aspose.slides/audioframe)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)