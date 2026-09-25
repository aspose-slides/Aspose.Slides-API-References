---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
ดึงขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### คืนค่า

หนึ่ง [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตภาพของรูปร่าง
             ในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งกลับเป็นตัวแทนของขอบเขตที่จัดชิดแกนของเนื้อหาทั้งหมด
             ที่สร้างขึ้นโดยรูปร่างในระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์
            
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเชิงลบหากเนื้อหาที่เรนเดอร์ขยาย
             เกินจุดกำเนิดของสไลด์
            
             ขอบเขตภาพจะคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์ เช่น
             การแปลง (เช่น การหมุน), ความกว้างของเส้นและการเชื่อมต่อ,
             การจัดวางข้อความและการล้น, รูปทรง SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ
             ที่ส่งผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง
            
             ขอบเขตที่ส่งกลับไม่ได้ถูกตัดให้เข้ากับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)