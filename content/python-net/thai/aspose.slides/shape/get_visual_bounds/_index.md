---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### ส่งคืน

อ็อบเจ็กต์ **aspose.slides.RectangleF** ที่แสดงขอบเขตภาพของรูปร่าง
             ในระบบพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ
สี่เหลี่ยมผืนผ้าที่ส่งกลับแสดงขอบเขตที่เรียงตามแกนของเนื้อหา
             ที่รูปสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์
            
ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
และอาจมีพิกัดเชิงลบหากเนื้อหาที่เรนเดอร์ขยายออกไปเกินจุดกำเนิดของสไลด์
            
ขอบเขตภาพจะคำนึงถึงแง่ที่เกี่ยวข้องกับการเรนเดอร์เช่น
             การแปลง (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ,
             การจัดวางข้อความและการล้น, เรขาคณิต SmartArt, และผลกระทบการจัดวางอื่น ๆ
             ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง
            
ขอบเขตที่ส่งกลับไม่ได้ถูกตัดให้ตรงกับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)