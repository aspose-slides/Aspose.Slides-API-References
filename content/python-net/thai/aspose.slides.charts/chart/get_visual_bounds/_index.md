---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### Returns

อ็อบเจ็กต์ [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงขอบเขตภาพของรูปร่าง
             ในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### Remarks
สี่เหลี่ยมที่ส่งกลับแสดงขอบเขตที่จัดแนวแกนของเนื้อหาทั้งหมด
             ที่ผลิตโดยรูปร่างระหว่างการเรนเดอร์ในพิกัดสไลด์

             
These bounds may differ from the shape's model bounds
( [`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยาย
             เกินจุดกำเนิดของสไลด์

             
The visual bounds take into account rendering-related aspects such as
การแปลง (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ,
การจัดวางข้อความและการล้น, SmartArt geometry, and other layout effects
ที่มีผลต่อการแสดงผลสุดท้ายของรูปร่าง.

             
The returned bounds are not clipped to the slide rectangle.



### See Also
* คลาส [`Chart`](/slides/python-net/th/aspose.slides.charts/chart)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)