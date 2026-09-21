---
title: remove method
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/layoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
ลบรูปแบบเลย์เอาต์ออกจากคอลเลกชัน.

```python
def remove(self, value):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | สไลด์เลย์เอาต์ที่จะลบออกจากคอลเลกชัน. |

### หมายเหตุ

1) เพื่อหลีกเลี่ยงการโยน PptxEditException ให้ตรวจสอบคุณสมบัติ HasDependingSlides ของเลย์เอาต์ก่อน.
            2) คุณสามารถใช้เมธอด [`ILayoutSlide.remove`](/slides/python-net/th/aspose.slides/ilayoutslide/remove) เพื่อทำให้โค้ดง่ายขึ้นได้.

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | จะถูกโยนเมื่อเลย์เอาต์ถูกใช้ในงานนำเสนอ (คุณสมบัติ HasDependingSlides ของมันเป็น true). |



### ดูเพิ่มเติม
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`LayoutSlideCollection`](/slides/python-net/th/aspose.slides/layoutslidecollection)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)