---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์ไว้

### คืนค่า

A [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่เป็นตัวแทนของขอบเขตภาพของรูปร่าง
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ
The returned rectangle represents the axis-aligned bounds of all content
             สี่เหลี่ยมที่คืนค่าจะเป็นตัวแทนของขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมด
             
             produced by the shape during rendering in slide coordinate space.
             ที่สร้างโดยรูปร่างขณะทำการเรนเดอร์ในพื้นที่พิกัดของสไลด์
            
             These bounds may differ from the shape's model bounds
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
             
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             
             and may contain negative coordinates if the rendered content extends
             และอาจมีค่าพิกัดเป็นลบหากเนื้อหาที่เรนเดอร์ขยายออกไป
             
             beyond the slide origin.
             เกินจุดกำเนิดของสไลด์
            
             
             The visual bounds take into account rendering-related aspects such as
             ขอบเขตภาพพิจารณาด้านที่เกี่ยวข้องกับการเรนเดอร์เช่น
             
             transformations (for example, rotation), stroke width and joins,
             การแปลง (เช่น การหมุน), ความกว้างของเส้นและการเชื่อมต่อ,
             
             text layout and overflow, SmartArt geometry, and other layout effects
             การจัดวางข้อความและการล้น, รูปร่าง SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ
             
             that influence the final rendered appearance of the shape.
             ที่มีผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง.
             
             
             The returned bounds are not clipped to the slide rectangle.
             ขอบเขตที่คืนค่าไม่ได้ถูกตัดคลิปให้เข้ากับสี่เหลี่ยมสไลด์.



### ดูเพิ่มเติม
* คลาส [`SectionZoomFrame`](/slides/python-net/th/aspose.slides/sectionzoomframe)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)