---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตที่มองเห็นของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### คืนค่า

A [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตภาพที่มองเห็นของรูปร่างในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมผืนผ้าที่ส่งคืนนี้แสดงขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมดที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยายออกไปนอกจุดกำเนิดของสไลด์

ขอบเขตที่มองเห็นคำนึงถึงแง่มุมที่เกี่ยวข้องกับการเรนเดอร์เช่นการแปลง (เช่น การหมุน), ความกว้างและการเชื่อมต่อของเส้นขอบ, การจัดรูปแบบข้อความและการล้น, เรขาคณิต SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ ที่ส่งผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง

ขอบเขตที่ส่งคืนจะไม่ถูกตัดต่อให้เข้ากับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)