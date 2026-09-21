---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาแบบเรนเดอร์แล้ว

### ผลลัพธ์

อ็อบเจ็กต์ **aspose.slides.RectangleF** ที่เป็นตัวแทนของขอบเขตภาพของรูปร่าง
             ในพิกัดสไลด์.



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งกลับนั้นเป็นตัวแทนของขอบเขตที่เรียงตามแกนของเนื้อหาทั้งหมดที่รูปร่างสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์
             
             ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
             และอาจมีพิกัดเป็นค่าติดลบหากเนื้อหาที่เรนเดอร์ขยายออกนอกต้นตอของสไลด์
             
             ขอบเขตภาพพิจารณาปัจจัยที่เกี่ยวข้องกับการเรนเดอร์เช่นการแปลงรูป (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ, การจัดเรียงข้อความและการล้น, SmartArt เรขาคณิต, และเอฟเฟกต์การจัดวางอื่น ๆ ที่ส่งผลต่อรูปลักษณ์สุดท้ายที่เรนเดอร์ของรูปร่าง
             
             ขอบเขตที่ส่งกลับจะไม่ถูกตัดให้พอดีกับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`SmartArtShape`](/slides/python-net/th/aspose.slides.smartart/smartartshape)
* โมดูล [`aspose.slides.smartart`](/slides/python-net/th/aspose.slides.smartart)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)