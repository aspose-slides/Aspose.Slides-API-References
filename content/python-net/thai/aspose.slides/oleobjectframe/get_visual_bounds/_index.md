---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET – เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่แสดงผล

### คืนค่า

อ็อบเจ็กต์ [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตภาพของรูปร่างในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่คืนค่าจะเป็นตัวแทนของขอบเขตที่เรียงตามแกนของเนื้อหาทั้งหมดที่รูปร่างสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีพิกัดเป็นค่าลบถ้าเนื้อหาที่แสดงผลขยายออกนอกจุดกำเนิดของสไลด์

ขอบเขตภาพจะคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์ เช่น การแปลง (เช่น การหมุน), ความกว้างของเส้นและการเชื่อมต่อ, การจัดเรียงข้อความและการล้น, รูปทรง SmartArt, และผลกระทบด้านการจัดรูปแบบอื่น ๆ ที่มีอิทธิพลต่อลักษณะที่แสดงผลสุดท้ายของรูปร่าง

ขอบเขตที่คืนค่านี้ไม่ได้ถูกตัดให้เข้ากับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`OleObjectFrame`](/slides/python-net/th/aspose.slides/oleobjectframe)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)