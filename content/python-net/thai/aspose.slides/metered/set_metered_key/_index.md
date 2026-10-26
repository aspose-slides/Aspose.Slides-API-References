---
title: set_metered_key method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
กำหนดคีย์สาธารณะและคีย์ส่วนตัวแบบตามการใช้
            หากคุณซื้อใบอนุญาตแบบตามการใช้ เมื่อเริ่มแอปพลิเคชัน API นี้ควรเรียกใช้ ซึ่งโดยปกติแล้วเพียงนี้ก็พอ
            อย่างไรก็ตาม หากการอัปโหลดข้อมูลการใช้งานล้มเหลวตลอดเวลาและเกิน 24 ชั่วโมง ใบอนุญาตจะเปลี่ยนเป็นสถานะประเมินผล
            เพื่อหลีกเลี่ยงกรณีนี้ คุณควรตรวจสอบสถานะใบอนุญาตเป็นระยะ หากอยู่ในสถานะประเมินผล ให้เรียก API นี้อีกครั้ง.


```python
def set_metered_key(self, public_key, private_key):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| public_key | **str** | คีย์สาธารณะ |
| private_key | **str** | คีย์ส่วนตัว |



### ดูเพิ่มเติม
* คลาส [`Metered`](/slides/python-net/th/aspose.slides/metered)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)