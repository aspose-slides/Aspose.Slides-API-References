---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
ดึงขอบเขตเชิงภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### คืนค่า

อ็อบเจ็กต์ **aspose.slides.RectangleF** ที่แทนขอบเขตเชิงภาพของรูปร่างในพิกัดสไลด์
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ
สี่เหลี่ยมที่ส่งคืนแสดงถึงขอบเขตที่ตั้งตามแกนของเนื้อหาทั้งหมด
             ที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
และอาจมีพิกัดเชิงลบหากเนื้อหาที่เรนเดอร์ขยาย
เกินจุดเริ่มต้นของสไลด์

ขอบเขตเชิงภาพพิจารณาด้านที่เกี่ยวข้องกับการเรนเดอร์เช่น
การแปลง (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ,
การจัดตำแหน่งข้อความและการล้น, เรขาคณิต SmartArt, และผลกระทบการจัดวางอื่นๆ
ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง

ขอบเขตที่ส่งคืนไม่ได้ถูกตัดให้เข้ากับสี่เหลี่ยมสไลด์.



### ดูเพิ่มเติม
* คลาส [`Table`](/slides/python-net/th/aspose.slides/table)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)