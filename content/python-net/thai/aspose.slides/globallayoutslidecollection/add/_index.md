---
title: add method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API
description: 
type: docs
url: /th/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
เพิ่มสไลด์เค้าโครงใหม่ไปยังงานนำเสนอ

### Returns

สไลด์ที่เพิ่ม



```python
def add(self, master, layout_type, layout_name):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide) | สไลด์มาสเตอร์สำหรับเค้าโครงใหม่ |
| layout_type | [`SlideLayoutType`](/slides/python-net/th/aspose.slides/slidelayouttype) | ประเภทเค้าโครงสำหรับเค้าโครงใหม่.<br/><br/>            ประเภทเค้าโครงที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            ประเภทเค้าโครงอื่น ๆ ที่ไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | ชื่อสำหรับเค้าโครงใหม่. หากชื่อที่ส่งมาใช้แล้วอยู่แล้ว จะทำให้เกิด ArgumentException.<br/><br/>            หากส่งพารามิเตอร์ None จะสร้างชื่อโดยอัตโนมัติตามประเภทเค้าโครงที่ส่ง<br/><br/>            (for example "Title Slide" or "1_Title Slide", "2_..", etc.). |

### Remarks

1) เค้าโครงที่เพิ่มสำหรับค่า SlideLayoutType.Custom ของ `layout_type` ไม่มีตัวเติมและไม่มีรูปร่าง.  
2) ตรงข้ามของเมธอดนี้คือเมธอด **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** ที่เข้าถึงได้ด้วย [`IMasterSlide.layout_slides`](/slides/python-net/th/aspose.slides/imasterslide/layout_slides) property.

### Exceptions

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | เกิดขึ้นหากค่าที่ไม่รองรับของพารามิเตอร์ `layout_type` ถูกส่ง. ประเภทเค้าโครงที่ไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | เกิดขึ้นหาก `master` เป็น None. |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นหาก `master` เป็นของงานนำเสนออื่น. |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นหากค่าชื่อเค้าโครง `layout_name` ถูกใช้แล้วในคอลเลกชันของเค้าโครงของ `master`. |

### See Also
* class [`GlobalLayoutSlideCollection`](/slides/python-net/th/aspose.slides/globallayoutslidecollection)
* class [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/th/aspose.slides/imasterslide)
* enumeration [`SlideLayoutType`](/slides/python-net/th/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)