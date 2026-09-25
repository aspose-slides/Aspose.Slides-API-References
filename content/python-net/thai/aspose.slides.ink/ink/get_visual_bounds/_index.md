---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
ดึงขอบเขตที่มองเห็นได้ของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### ผลลัพธ์

อ็อบเจกต์ [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตที่มองเห็นได้ของรูปร่างในพิกัดสไลด์
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่คืนมานี้แสดงขอบเขตที่เรียงตามแกนของเนื้อหาทั้งหมดที่รูปร่างสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์
             
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยายออกไปเกินจุดเริ่มต้นของสไลด์
             
             ขอบเขตที่มองเห็นคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์เช่นการแปลง (เช่น การหมุน), ความกว้างของเส้นและการเชื่อม,
             การจัดรูปแบบข้อความและการล้น, รูปร่างของ SmartArt, และผลกระทบการจัดวางอื่น ๆ ที่ส่งผลต่อการแสดงผลสุดท้ายของรูปร่าง
             
             ขอบเขตที่คืนมาจะไม่ถูกตัดให้พอดีกับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`Ink`](/slides/python-net/th/aspose.slides.ink/ink)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides.ink`](/slides/python-net/th/aspose.slides.ink)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)