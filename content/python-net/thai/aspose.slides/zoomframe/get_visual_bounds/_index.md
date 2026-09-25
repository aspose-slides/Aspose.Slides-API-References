---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### ผลลัพธ์

A [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตภาพของรูปร่าง
             ในพิกัดสไลด์.



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งกลับแสดงขอบเขตที่จัดแนวแกนของเนื้อหาทั้งหมดที่สร้างโดยรูปร่าง
             ผลิตระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์.
            
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเป็นลบหากเนื้อหาที่เรนเดอร์ขยายออกไป
             นอกจุดกำเนิดของสไลด์.
            
             ขอบเขตภาพจะคำนึงถึงแง่มุมที่เกี่ยวข้องกับการเรนเดอร์เช่น
             การแปลง (เช่น การหมุน), ความกว้างและการเชื่อมต่อของเส้นขอบ,
             การจัดวางข้อความและการล้น, เรขาคณิต SmartArt, และผลแบบเลย์เอาต์อื่น ๆ
             ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง.
            
             ขอบเขตที่ส่งกลับจะไม่ได้ถูกตัดให้ตรงกับสี่เหลี่ยมสไลด์.



### ดูเพิ่มเติม
* คลาส [`ZoomFrame`](/slides/python-net/th/aspose.slides/zoomframe)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)