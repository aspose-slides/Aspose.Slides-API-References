---
title: insert method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
แทรกสไลด์เลเอาต์ใหม่ในตำแหน่งที่ระบุของคอลเลกชัน

### Returns
สไลด์ที่ถูกแทรก

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | ดัชนีของสไลด์ใหม่ |
| layout_type | [`SlideLayoutType`](/slides/python-net/th/aspose.slides/slidelayouttype) | ประเภทเลเอาต์สำหรับเลเอาต์ใหม่<br/><br/>            ประเภทเลเอาต์ที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            ประเภทเลเอาต์อื่น ๆ ยังไม่รองรับ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | ชื่อสำหรับเลเอาต์ใหม่ หากชื่อที่ให้เป็นที่ใช้แล้วจะทำให้เกิด ArgumentException.<br/><br/>            หากพารามิเตอร์เป็น None จะสร้างชื่อโดยอัตโนมัติตามประเภทเลเอาต์ที่ส่งเข้า (เช่น "Title Slide" หรือ "1_Title Slide", "2_..", เป็นต้น). |

### Remarks
เลเอาต์ที่แทรกสำหรับค่า SlideLayoutType.Custom ของ `layout_type` 
            ไม่มีตัวแปรแทนและไม่มีรูปทรง

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | ถูกโยนเมื่อค่าพารามิเตอร์ `layout_type` ที่ไม่รองรับถูกส่งเข้า ประเภทเลเอาต์ที่ไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | ถูกโยนเมื่อค่า `layout_name` ของเลเอาต์มีอยู่แล้วใน <br/>            คอลเลกชันของเลเอาต์นี้. |

### See Also
* class [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* class [`MasterLayoutSlideCollection`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/th/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)