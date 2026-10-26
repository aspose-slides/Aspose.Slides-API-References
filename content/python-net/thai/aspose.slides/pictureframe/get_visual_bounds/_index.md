---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### ผลลัพธ์

A [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef) ที่แสดงถึงขอบเขตภาพของรูปทรง
             ในพิกัดสไลด์.



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่คืนค่าจะเป็นตัวแทนของขอบเขตที่จัดแนวแกนของเนื้อหาทั้งหมดที่รูปทรงสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์
             
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปทรง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเชิงลบหากเนื้อหาที่เรนเดอร์ขยายเกินจุดเริ่มต้นของสไลด์
             
             ขอบเขตภาพพิจารณาถึงแง่ที่เกี่ยวกับการเรนเดอร์เช่นการแปลง (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ, รูปแบบข้อความและการล้น, รูปร่าง SmartArt, และผลกระทบการจัดวางอื่น ๆ ที่มีอิทธิพลต่อการแสดงผลสุดท้ายของรูปทรง
             
             ขอบเขตที่คืนค่านั้นไม่ได้ถูกคลิปให้เข้ากับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`PictureFrame`](/slides/python-net/th/aspose.slides/pictureframe)
* คลาส [`RectangleF`](/slides/python-net/th/aspose.slides/rectanglef)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)