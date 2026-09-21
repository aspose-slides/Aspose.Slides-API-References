---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### ผลลัพธ์
อ็อบเจ็กต์ **aspose.slides.RectangleF** ที่แสดงขอบเขตภาพของรูปร่างในระบบพิกัดของสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ
สี่เหลี่ยมที่คืนค่าจะเป็นตัวแทนของขอบเขตที่เรียงตามแกนของเนื้อหาทั้งหมดที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพื้นที่พิกัดของสไลด์  
ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีค่าพิกัดเป็นลบหากเนื้อหาที่เรนเดอร์ขยายเกินจุดเริ่มต้นของสไลด์  
ขอบเขตภาพจะคำนึงถึงแง่มุมที่เกี่ยวข้องกับการเรนเดอร์ เช่น การแปลง (เช่น การหมุน), ความกว้างของเส้นและการเชื่อมต่อ, การจัดวางข้อความและการล้นข้อความ, เรขาคณิตของ SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ ที่ส่งผลต่อรูปลักษณ์ขั้นสุดท้ายของรูปร่างที่เรนเดอร์  
ขอบเขตที่คืนค่าไม่ได้ถูกตัดให้พอดีกับสี่เหลี่ยมของสไลด์



### ดูเพิ่มเติม
* คลาส [`InkActions`](/slides/python-net/th/aspose.slides.ink/inkactions)
* โมดูล [`aspose.slides.ink`](/slides/python-net/th/aspose.slides.ink)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)