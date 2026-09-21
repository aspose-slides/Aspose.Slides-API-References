---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
รับค่าขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์

### ผลลัพธ์

**aspose.slides.RectangleF** ที่แสดงขอบเขตภาพของรูปร่าง
             ในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่คืนค่าจะเป็นขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมด
             ที่รูปร่างสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์
             
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตแบบจำลองของรูปร่าง
             ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยายเกินจุดกำเนิดของสไลด์
             
             ขอบเขตภาพจะพิจารณาปัจจัยที่เกี่ยวข้องกับการเรนเดอร์ เช่น
             การแปลง (เช่น การหมุน), ความกว้างของเส้นและการเชื่อมต่อ,
             การจัดตำแหน่งข้อความและการล้น, รูปร่าง SmartArt, และผลกระทบการจัดรูปแบบอื่นๆ
             
             ขอบเขตที่คืนค่าไม่ได้ถูกตัดคลิปให้เล็กลงตามสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`PictureFrame`](/slides/python-net/th/aspose.slides/pictureframe)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)