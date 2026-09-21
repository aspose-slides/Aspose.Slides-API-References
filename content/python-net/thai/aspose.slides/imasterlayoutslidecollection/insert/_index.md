---
title: insert method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
แทรกสไลด์เลย์เอาต์ใหม่ลงในตำแหน่งที่ระบุของคอลเลกชัน

### คืนค่า

สไลด์ที่แทรก

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีของสไลด์ใหม่ |
| layout_type | [`SlideLayoutType`](/slides/python-net/th/aspose.slides/slidelayouttype) | ประเภทเลย์เอาต์สำหรับเลย์เอาต์ใหม่.<br/><br/>            ประเภทเลย์เอาต์ที่สนับสนุน: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            ประเภทเลย์เอาต์อื่น ๆ ที่ยังไม่สนับสนุน: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | ชื่อสำหรับเลย์เอาต์ใหม่ หากชื่อที่ส่งเข้ามาใช้แล้ว จะทำให้เกิด ArgumentException.<br/><br/>            หากส่งค่า None จะสร้างชื่อโดยอัตโนมัติตามประเภทเลย์เอาต์ที่ส่งเข้ามา (เช่น “Title Slide” หรือ “1_Title Slide”, “2_..” เป็นต้น). |

### หมายเหตุ

เลย์เอาต์ที่แทรกสำหรับค่า SlideLayoutType.Custom ของ `layout_type` ไม่มีตัวแทนที่วางไว้และไม่มีรูปร่าง

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | เกิดขึ้นเมื่อส่งค่าพารามิเตอร์ `layout_type` ที่ไม่รองรับ ประเภทเลย์เอาต์ที่ยังไม่สนับสนุน: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นเมื่อค่า `layout_name` ของชื่อเลย์เอาต์ถูกใช้แล้วในคอลเลกชันนี้ของเลย์เอาต์ |

### ดูเพิ่มเติม
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`IMasterLayoutSlideCollection`](/slides/python-net/th/aspose.slides/imasterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/th/aspose.slides/slidelayouttype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)