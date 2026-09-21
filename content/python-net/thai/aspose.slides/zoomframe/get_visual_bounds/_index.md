---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตเชิงภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### คืนค่า
อ็อบเจกต์ **aspose.slides.RectangleF** ที่แสดงขอบเขตเชิงภาพของรูปร่าง
             ในระบบพิกัดของสไลด์.



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ
สี่เหลี่ยมที่ส่งกลับแสดงขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมด
             ที่รูปสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดของสไลด์
             
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตแบบโมเดลของรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยายเกินต้นทางของสไลด์
             
             ขอบเขตเชิงภาพจะคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์เช่น
             การแปลง (เช่น การหมุน), ความกว้างและการต่อของเส้นขอบ,
             การจัดวางข้อความและการล้น, รูปร่างของ SmartArt, และผลกระทบการจัดวางอื่น ๆ
             ที่ส่งผลต่อรูปลักษณ์ขั้นสุดท้ายของรูปร่างเมื่อเรนเดอร์
             
             ขอบเขตที่ส่งกลับไม่ได้ถูกตัดให้พอดีกับสี่เหลี่ยมของสไลด์



### ดูเพิ่มเติม
* คลาส [`ZoomFrame`](/slides/python-net/th/aspose.slides/zoomframe)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)