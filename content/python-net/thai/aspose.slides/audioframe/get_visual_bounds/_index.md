---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
รับขอบเขตเชิงภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### ผลลัพธ์

A **aspose.slides.RectangleF** ที่แสดงขอบเขตเชิงภาพของรูปทรงในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่ส่งกลับจะเป็นตัวแทนของขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมดที่รูปทรงสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปทรง ([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height)) และอาจมีพิกัดเป็นค่าลบหากเนื้อหาที่เรนเดอร์ขยายเกินจุดต้นของสไลด์

ขอบเขตเชิงภาพจะพิจารณาแง่มุมที่เกี่ยวข้องกับการเรนเดอร์เช่นการแปลง (เช่น การหมุน), ความกว้างของเส้นขอบและการเชื่อมต่อ, การจัดวางข้อความและการโอเวอร์โฟลว์, รูปร่างของ SmartArt, และผลกระทบการจัดวางอื่น ๆ ที่มีอิทธิพลต่อลักษณะการแสดงผลขั้นสุดท้ายของรูปทรง

ขอบเขตที่ส่งกลับจะไม่ได้ถูกคลิปให้ตรงกับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`AudioFrame`](/slides/python-net/th/aspose.slides/audioframe)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)