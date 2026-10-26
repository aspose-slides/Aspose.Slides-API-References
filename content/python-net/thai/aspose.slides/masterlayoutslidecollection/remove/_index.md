---
title: remove method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
ลบเค้าโครงออกจากคอลเลกชัน.

```python
def remove(self, value):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | สไลด์เค้าโครงที่ต้องลบออกจากคอลเลกชัน. |

### หมายเหตุ

1) เพื่อหลีกเลี่ยงการโยน PptxEditException ให้ตรวจสอบคุณสมบัติ HasDependingSlides ของเค้าโครงก่อน.
2) คุณสามารถใช้เมธอด [`ILayoutSlide.remove`](/slides/python-net/th/aspose.slides/ilayoutslide/remove) เพื่อทำให้โค้ดง่ายขึ้น.

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | เกิดขึ้นถ้าเค้าโครงถูกใช้ในงานนำเสนอ (คุณสมบัติ HasDependingSlides ของมันเป็น true). |

### ดูเพิ่มเติม
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`MasterLayoutSlideCollection`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)