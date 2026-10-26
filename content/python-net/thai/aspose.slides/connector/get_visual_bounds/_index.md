---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
รับขอบเขตเชิงภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### คืนค่า

อ็อบเจ็กต์ [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงถึงขอบเขตเชิงภาพของรูปร่างในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งคืนแสดงถึงขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมด
             ที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์
             
             
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเป็นลบหากเนื้อหาที่เรนเดอร์ขยายออกไปนอกต้นจุดของสไลด์
             
             
             ขอบเขตเชิงภาพคำนึงถึงแง่มุมที่เกี่ยวข้องกับการเรนเดอร์เช่น
             การแปลง (เช่น การหมุน), ความกว้างของเส้นขอบและการต่อเชื่อม,
             การจัดวางข้อความและการล้น, รูปทรงของ SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ
             ที่ส่งผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง.
             
             
             ขอบเขตที่ส่งคืนไม่ได้ถูกตัดต่อให้พอดีกับสี่เหลี่ยมสไลด์.



### ดูเพิ่มเติม
* คลาส [`Connector`](/slides/python-net/th/aspose.slides/connector)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)