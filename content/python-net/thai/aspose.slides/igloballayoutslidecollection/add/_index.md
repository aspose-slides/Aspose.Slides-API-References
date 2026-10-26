---
title: add method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
เพิ่มสไลด์เค้าโครงการใหม่ลงในงานนำเสนอ

### คืนค่า
สไลด์ที่เพิ่มแล้ว.

```python
def add(self, master, layout_type, layout_name):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide) | สไลด์แม่สำหรับเค้าโครงการใหม่. |
| layout_type | [`SlideLayoutType`](/slides/python-net/th/aspose.slides/slidelayouttype) | ประเภทเค้าโครงการสำหรับเค้าโครงการใหม่.<br/><br/>            ประเภทเค้าโครงการที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            ประเภทเค้าโครงการอื่น ๆ ที่ไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | ชื่อสำหรับเค้าโครงการใหม่ หากชื่อที่ส่งเข้ามาใช้แล้วจะเกิด ArgumentException.<br/><br/>            หากส่งพารามิเตอร์ None จะสร้างชื่อโดยอัตโนมัติตามประเภทเค้าโครงการที่ส่งเข้ามา <br/><br/>            (เช่น "Title Slide" หรือ "1_Title Slide", "2_..", เป็นต้น). |

### หมายเหตุ
1) เค้าโครงการที่เพิ่มสำหรับค่า SlideLayoutType.Custom ของ `layout_type` 
            ไม่มีตัวแสดงตำแหน่งและไม่มีรูปทรง.
2) รูปแบบของเมธอดนี้คือเมธอด **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste**
            ที่เข้าถึงด้วยคุณสมบัติ [`IMasterSlide.layout_slides`](/slides/python-net/th/aspose.slides/imasterslide/layout_slides).

### ข้อยกเว้น
| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | เกิดข้อผิดพลาดหากค่า `layout_type` ที่ส่งเข้ามาไม่รองรับ. ประเภทเค้าโครงการที่ไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | เกิดข้อผิดพลาดหาก `master` มีค่า None. |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดข้อผิดพลาดหาก `master` เป็นของงานนำเสนออื่น. |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดข้อผิดพลาดหากค่า `layout_name` ของชื่อเค้าโครงการถูกใช้แล้วใน <br/>            คอลเลกชันของเค้าโครงการของ `master`. |

### ดูเพิ่มเติม
* คลาส [`IGlobalLayoutSlideCollection`](/slides/python-net/th/aspose.slides/igloballayoutslidecollection)
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide)
* enumeration [`SlideLayoutType`](/slides/python-net/th/aspose.slides/slidelayouttype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)