---
title: remove_at method
second_title: Aspose.Slides สำหรับ Python ผ่านการอ้างอิง API ของ .NET
description: 
type: docs
url: /th/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน

```python
def remove_at(self, index):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ขององค์ประกอบที่จะลบ |

### หมายเหตุ

1) เพื่อหลีกเลี่ยงการโยน PptxEditException ให้ตรวจสอบคุณสมบัติ HasDependingSlides ของ layout ก่อน
2) คุณสามารถใช้เมธอด [`ILayoutSlide.remove`](/slides/python-net/th/aspose.slides/ilayoutslide/remove) เพื่อทำให้โค้ดง่ายขึ้น

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | ถูกโยนถ้า layout ถูกใช้ในงานนำเสนอ (คุณสมบัติ HasDependingSlides ของมันเป็น true) |

### ดูเพิ่มเติม
* คลาส [`MasterLayoutSlideCollection`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)