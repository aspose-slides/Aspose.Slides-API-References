---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่แสดงผล

### Returns
A [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตภาพของรูปร่างในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```

### หมายเหตุ
สี่เหลี่ยมที่ส่งกลับแสดงขอบเขตที่จัดแนวแกนของเนื้อหาทั้งหมดที่รูปร่างสร้างขึ้นระหว่างการแสดงผลในพื้นที่พิกัดสไลด์  
ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตของโมเดลรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีค่าพิกัดเป็นลบหากเนื้อหาที่แสดงผลขยายเกินต้นทางของสไลด์  
ขอบเขตภาพคำนึงถึงแง่มุมที่เกี่ยวกับการแสดงผล เช่น การแปลงรูป (เช่น การหมุน), ความกว้างของเส้นและการเชื่อมต่อ, การจัดวางข้อความและการล้น, รูปร่างของ SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ ที่มีผลต่อการปรากฏสุดท้ายของรูปร่างที่แสดงผล  
ขอบเขตที่ส่งกลับจะไม่ถูกตัดให้เข้ากับสี่เหลี่ยมสไลด์

### ดูเพิ่มเติม
* คลาส [`AutoShape`](/slides/python-net/th/aspose.slides/autoshape)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)