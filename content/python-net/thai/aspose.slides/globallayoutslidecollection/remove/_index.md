---
title: remove method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/globallayoutslidecollection/remove/
weight: 40
---
## remove(self, value) {#ilayoutslide}
ลบเลย์เอาต์ออกจากคอลเลกชัน.

```python
def remove(self, value):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | สไลด์เลย์เอาต์ที่ต้องการลบออกจากคอลเลกชัน. |

### หมายเหตุ

1) เพื่อหลีกเลี่ยงการโยน PptxEditException ให้ตรวจสอบคุณสมบัติ HasDependingSlides ของ layout ก่อน.
2) คุณยังสามารถใช้เมธอด [`ILayoutSlide.remove`](/slides/python-net/th/aspose.slides/ilayoutslide/remove) เพื่อทำให้โค้ดง่ายขึ้น.

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | เกิดข้อผิดพลาดหากเลย์เอาต์ถูกใช้ในงานนำเสนอ (คุณสมบัติ HasDependingSlides ของมันเป็น true). |

### ดูเพิ่มเติม
* คลาส [`GlobalLayoutSlideCollection`](/slides/python-net/th/aspose.slides/globallayoutslidecollection)
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)