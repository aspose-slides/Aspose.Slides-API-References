---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับค่าขอบเขตเชิงภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### ค่าที่ส่งกลับ

A **aspose.slides.RectangleF** ที่แสดงขอบเขตเชิงภาพของรูปร่างในพิกัดของสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งคืนแสดงขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมด
             ที่รูปร่างสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์
            
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดลบหากเนื้อหาที่เรนเดอร์ขยายเกินจุดกำเนิดของสไลด์
            
             ขอบเขตเชิงภาพพิจารณาถึงแง่มุมที่เกี่ยวข้องกับการเรนเดอร์เช่นการแปลง (เช่น การหมุน), ความกว้างและการเชื่อมต่อของเส้นขอบ, การจัดรูปแบบข้อความและการล้น, รูปร่างของ SmartArt, และผลกระทบการจัดรูปแบบอื่น ๆ ที่มีผลต่อรูปลักษณ์ขั้นสุดท้ายของรูปร่างที่เรนเดอร์
            
             ขอบเขตที่ส่งคืนไม่ได้ถูกตัดให้พอดีกับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)