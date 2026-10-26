---
title: register_ink_effect_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
ลงทะเบียนรูปภาพไปยังคอลเลกชันของรูปภาพที่กำหนดเองที่ใช้เพื่อจำลองเอฟเฟกต์ภาพสำหรับแปรงหมึก
            รูปภาพเหล่านี้จะใช้เมื่อเรนเดอร์หมึกด้วยค่า [`InkEffectType`](/slides/python-net/th/aspose.slides.ink/inkeffecttype) เฉพาะ,
            เช่น Galaxy, Rainbow ฯลฯ โดยการให้รูปภาพของคุณเอง คุณสามารถควบคุมการแสดงผลของแต่ละเอฟเฟกต์หมึกได้


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/th/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/th/aspose.slides/iimage) |  |

### หมายเหตุ

วิธีนี้ช่วยให้เปลี่ยนเทกเจอร์เอฟเฟกต์หมึกเริ่มต้นด้วยเทกเจอร์ที่กำหนดโดยผู้ใช้,
            ซึ่งมีประโยชน์อย่างยิ่งเมื่อสินทรัพย์เริ่มต้นถูกจำกัดโดยลิขสิทธิ์หรือไม่มีให้ใช้งานในขณะรันไทม์
            แต่ละคู่ค่าที่ลงทะเบียนต้องเชื่อมโยงค่า [`InkEffectType`](/slides/python-net/th/aspose.slides.ink/inkeffecttype) กับวัตถุ [`IImage`](/slides/python-net/th/aspose.slides/iimage) ที่สอดคล้องกัน (เช่น Bitmap หรืออินเทอร์เฟซภาพของ Aspose)

### ดูเพิ่มเติม
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* คลาส [`Ink`](/slides/python-net/th/aspose.slides.ink/ink)
* enumeration [`InkEffectType`](/slides/python-net/th/aspose.slides.ink/inkeffecttype)
* โมดูล [`aspose.slides.ink`](/slides/python-net/th/aspose.slides.ink)
* library [`Aspose.Slides`](/slides/python-net)