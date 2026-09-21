---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
ดึงขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### คืนค่า

อ็อบเจกต์ **aspose.slides.RectangleF** ที่เป็นตัวแทนของขอบเขตภาพของรูปร่าง
             ในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งกลับมานี้เป็นตัวแทนของขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมดที่รูปร่างสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์
            
            ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีพิกัดเป็นค่าติดลบหากเนื้อหาที่เรนเดอร์ขยายออกไปเกินจุดเริ่มต้นของสไลด์
            
            ขอบเขตภาพพิจารณาปัจจัยที่เกี่ยวกับการเรนเดอร์เช่นการแปลงรูป (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ, การจัดวางข้อความและการล้น, เรขาคณิตของ SmartArt, และผลกระทบการจัดวางอื่น ๆ ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง
            
            ขอบเขตที่ส่งกลับจะไม่ถูกคลิปให้พอดีกับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`SummaryZoomSection`](/slides/python-net/th/aspose.slides/summaryzoomsection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)