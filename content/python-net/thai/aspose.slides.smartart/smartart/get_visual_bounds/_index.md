---
title: get_visual_bounds method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
รับขอบเขตเชิงภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว

### ผลลัพธ์

A **aspose.slides.RectangleF** ที่แสดงถึงขอบเขตเชิงภาพของรูปร่าง
ในพิกัดสไลด์



```python
def get_visual_bounds(self):
    ...
```


### หมายเหตุ

สี่เหลี่ยมที่คืนค่าจะเป็นขอบเขตที่จัดแนวตามแกนของเนื้อหาทั้งหมด
ที่รูปร่างสร้างขึ้นระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์

ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง
([`Shape.x`](/slides/python-net/th/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/th/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/th/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/th/aspose.slides/shape/height))
และอาจมีค่าพิกัดลบหากเนื้อหาที่เรนเดอร์ขยายออกไปเกินจุดเริ่มต้นของสไลด์

ขอบเขตเชิงภาพคำนึงถึงแง่มุมที่เกี่ยวข้องกับการเรนเดอร์เช่น
การแปลง (เช่น การหมุน) ความกว้างของเส้นและการเชื่อมต่อ,
การจัดวางข้อความและการล้น, เรขาคณิต SmartArt, และเอฟเฟกต์การจัดวางอื่น ๆ
ที่มีผลต่อการแสดงผลสุดท้ายของรูปร่าง

ขอบเขตที่คืนค่าไม่ได้ถูกตัดให้เข้ากับสี่เหลี่ยมสไลด์



### ดูเพิ่มเติม
* คลาส [`SmartArt`](/slides/python-net/th/aspose.slides.smartart/smartart)
* มอดูล [`aspose.slides.smartart`](/slides/python-net/th/aspose.slides.smartart)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)