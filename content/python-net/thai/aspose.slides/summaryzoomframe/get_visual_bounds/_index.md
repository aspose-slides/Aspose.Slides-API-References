---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
ดึงขอบเขตที่มองเห็นของรูปร่างซึ่งคำนวณจากเนื้อหาที่แสดงผล

### ผลลัพธ์

A **aspose.slides.RectangleF** ที่แสดงขอบเขตที่มองเห็นของรูปร่างในระบบพิกัดของสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งกลับแสดงขอบเขตที่เรียงตามแกนของเนื้อหาทั้งหมดที่รูปร่างสร้างขึ้นระหว่างการแสดงผลในพื้นที่พิกัดของสไลด์
             
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่แสดงผลขยายเกินจุดกำเนิดของสไลด์
             
             ขอบเขตที่มองเห็นคำนึงถึงแง่มุมที่เกี่ยวกับการแสดงผลเช่นการแปลง (ตัวอย่างเช่น การหมุน), ความกว้างของเส้นและการเชื่อมต่อ, การจัดวางข้อความและการล้น, เรขาคณิตของ SmartArt, และผลกระทบการจัดวางอื่นๆ ที่มีอิทธิพลต่อรูปลักษณ์สุดท้ายของรูปร่างที่แสดงผล
             
             ขอบเขตที่ส่งกลับจะไม่ถูกตัดขอบตามสี่เหลี่ยมของสไลด์



### ดูเพิ่มเติม
* คลาส [`SummaryZoomFrame`](/slides/python-net/th/aspose.slides/summaryzoomframe)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ห้องสมุด [`Aspose.Slides`](/slides/python-net)