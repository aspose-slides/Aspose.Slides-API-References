---
title: get_object_storing_location method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Determines where object should be stored.
            This method is called once for each object id.
            It is not guaranteed that there won't be two objects with same data, semanticName and contentType but with different id.

### ผลลัพธ์
การตัดสินใจ

```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| id | **int** | รหัสอ็อบเจ็กต์. รหัสนี้มีความเป็นเอกลักษณ์ทั่วทั้งการดำเนินการบันทึก. |
| entity_data | **bytes** | ข้อมูลไบนารีของอ็อบเจ็กต์. พารามิเตอร์นี้อาจเป็น None หากข้อมูลไบนารีของอ็อบเจ็กต์ยังไม่ได้สร้าง. |
| semantic_name | **str** | ข้อความสั้นบางส่วนที่อธิบายความหมายของอ็อบเจ็กต์. ตัวควบคุมอาจใช้เป็นส่วนหนึ่งของชื่ออ็อบเจ็กต์ภายนอก, แต่การทำให้ชื่อเป็นเอกลักษณ์และมีเฉพาะอักขระที่อนุญาตเป็นหน้าที่ของตัวจัดการ. |
| content_type | **str** | ประเภท MIME ของอ็อบเจ็กต์. |
| recomended_extension | **str** | นามสกุลไฟล์ที่แนะนำสำหรับประเภท MIME นี้. |

### ดูเพิ่มเติม
* คลาส [`ILinkEmbedController`](/slides/python-net/th/aspose.slides.export/ilinkembedcontroller)
* enumeration [`LinkEmbedDecision`](/slides/python-net/th/aspose.slides.export/linkembeddecision)
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)