---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
ดึงขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### คืนค่า

อ็อบเจ็กต์ [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตภาพของรูปทรงในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่คืนค่าจะเป็นตัวแทนขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมดที่รูปทรงสร้างขึ้นระหว่างการเรนเดอร์ในระบบพิกัดสไลด์

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปทรง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมี **ค่าพิกัดเป็นลบ** หากเนื้อหาที่เรนเดอร์ขยายออกไปเกินจุดเริ่มต้นของสไลด์

ขอบเขตภาพจะคำนึงถึงด้านที่เกี่ยวข้องกับการเรนเดอร์ เช่น การแปลง (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ, การจัดรูปแบบข้อความและการล้น, รูปร่างของ SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ ที่ส่งผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปทรง

ขอบเขตที่คืนค่าไม่ได้ถูกตัดต่อให้พอดีกับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)