---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### คืนค่า

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             ในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งคืนแสดงถึงขอบเขตที่จัดตามแกนของเนื้อหาทั้งหมด
             ที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์
            
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยายเกินต้นจOriginของสไลด์
            
             ขอบเขตภาพคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์เช่น การแปลงรูป (เช่น การหมุน), ความกว้างเส้นขอบและการเชื่อมต่อ, การจัดวางข้อความและการล้น, รูปร่าง SmartArt, และผลกระทบการจัดวางอื่น ๆ ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง
            
             ขอบเขตที่ส่งคืนไม่ได้ถูกตัดให้พอดีกับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`SectionZoomFrame`](/slides/python-net/th/aspose.slides/sectionzoomframe)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)