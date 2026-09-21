---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
รับขอบเขตการแสดงผลของรูปร่างซึ่งคำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### ค่าที่ส่งคืน

อ็อบเจ็กต์ **aspose.slides.RectangleF** ที่แสดงขอบเขตการแสดงผลของรูปร่าง
             ในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งคืนแสดงถึงขอบเขตที่จัดแนวแกนของเนื้อหาทั้งหมดที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์
             
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตของโมเดลรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีโค้อร์ดิเนตเชิงลบหากเนื้อหาที่เรนเดอร์ขยายเกินต้นจุดของสไลด์
             
             ขอบเขตการแสดงผลคำนึงถึงด้านที่เกี่ยวข้องกับการเรนเดอร์ เช่น การแปลง (เช่น การหมุน), ความกว้างเส้นและการเชื่อมต่อ,
             การจัดวางข้อความและการล้น, รูปร่าง SmartArt, และผลกระทบจากการจัดวางอื่น ๆ ที่มีผลต่อการแสดงผลสุดท้ายของรูปร่าง
             
             ขอบเขตที่ส่งคืนจะไม่ถูกคลิปให้เข้ากับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`VideoFrame`](/slides/python-net/th/aspose.slides/videoframe)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)