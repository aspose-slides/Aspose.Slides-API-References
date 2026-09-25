---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
รับขอบเขตที่มองเห็นของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### Returns

A [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตที่มองเห็นของรูปร่าง
             ในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### Remarks

สี่เหลี่ยมผืนผ้าที่ส่งคืนแสดงขอบเขตที่แนวแกนของเนื้อหาทั้งหมด
             ที่รูปร่างสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์
            
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยายออกไปเกินจุดกำเนิดของสไลด์
            
             ขอบเขตที่มองเห็นคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์เช่น
             การแปลงรูป (เช่น การหมุน), ความกว้างเส้นขอบและการเชื่อมต่อ,
             การจัดวางข้อความและการล้น, เรขาคณิต SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ
             ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง
            
             ขอบเขตที่ส่งคืนไม่ได้ถูกตัดให้เข้ากับสี่เหลี่ยมสไลด์



### See Also
* คลาส [`SmartArtShape`](/slides/python-net/th/aspose.slides.smartart/smartartshape)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides.smartart`](/slides/python-net/th/aspose.slides.smartart)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)