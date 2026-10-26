---
title: remove_at method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน

```python
def remove_at(self, index):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ขององค์ประกอบที่ต้องการลบ |

### หมายเหตุ

เพื่อหลีกเลี่ยงการโยน PptxEditException ให้ตรวจสอบคุณสมบัติ HasDependingSlides ของมาสเตอร์ก่อน

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | โยนเมื่อมาสเตอร์ที่ต้องลบถูกใช้ในพรีเซนเทชัน (คุณสมบัติ HasDependingSlides ของมันเป็น true) |

### ดูเพิ่มเติม
* คลาส [`MasterSlideCollection`](/slides/python-net/th/aspose.slides/masterslidecollection)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)