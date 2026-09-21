---
title: remove method
second_title: อ้างอิง API Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
ลบเลย์เอาต์ออกจากคอลเลกชัน.

```python
def remove(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | สไลด์เลย์เอาต์ที่ต้องลบออกจากคอลเลกชัน. |

### หมายเหตุ

1) เพื่อหลีกเลี่ยงการโยน PptxEditException ให้ตรวจสอบคุณสมบัติ HasDependingSlides ของ layout ก่อน.
2) คุณสามารถใช้เมธ็อด [`ILayoutSlide.remove`](/slides/python-net/th/aspose.slides/ilayoutslide/remove) เพื่อทำให้โค้ดง่ายขึ้น.

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | จะถูกโยนหาก layout ถูกใช้ใน presentation (คุณสมบัติ HasDependingSlides ของมันเป็น true). |

### ดูเพิ่มเติม
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`ILayoutSlideCollection`](/slides/python-net/th/aspose.slides/ilayoutslidecollection)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)