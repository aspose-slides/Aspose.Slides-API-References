---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
ดึงขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### คืนค่า

หนึ่ง **aspose.slides.RectangleF** ที่แสดงขอบเขตภาพของรูปร่างในพิกัดของสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งกลับแสดงขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมดที่รูปร่างสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดของสไลด์

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีพิกัดเป็นค่าติดลบหากเนื้อหาที่เรนเดอร์ขยายออกไปเกินจุดกำเนิดของสไลด์

ขอบเขตภาพคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์ เช่น การแปลงรูป (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ, การจัดวางข้อความและการล้น, รูปร่างของ SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ ที่มีผลต่อรูปลักษณ์สุดท้ายของรูปร่างที่เรนเดอร์

ขอบเขตที่ส่งกลับจะไม่ถูกคลิปให้พอดีกับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`Chart`](/slides/python-net/th/aspose.slides.charts/chart)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)