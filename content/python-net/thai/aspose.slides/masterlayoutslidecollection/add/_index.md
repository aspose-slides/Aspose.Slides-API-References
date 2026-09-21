---
title: add method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
เพิ่มสไลด์เลย์เอาต์ใหม่ไปที่ตำแหน่งสุดท้ายของคอลเลกชัน

### ส่งคืน

สไลด์ที่เพิ่ม

```python
def add(self, layout_type, layout_name):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/th/aspose.slides/slidelayouttype) | ชนิดของเลย์เอาต์สำหรับเลย์เอาต์ใหม่.<br/><br/>            ชนิดของเลย์เอาต์ที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            ชนิดของเลย์เอาต์อื่น ๆ ที่ยังไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | ชื่อสำหรับเลย์เอาต์ใหม่. หากชื่อที่ส่งเข้ามาใช้งานอยู่แล้วจะทำให้เกิด ArgumentException.<br/><br/>            หากพารามิเตอร์เป็น None จะสร้างชื่อโดยอัตโนมัติตามชนิดของเลย์เอาต์ที่ส่งเข้ามา <br/><br/>            (เช่น "Title Slide" หรือ "1_Title Slide", "2_..", เป็นต้น). |

### หมายเหตุ

1) เลย์เอาต์ที่เพิ่มสำหรับค่า SlideLayoutType.Custom ของ `layout_type` 
            ไม่มีตัวแทนที่วางไว้และไม่มีรูปร่างใดๆ.
2) วิธีการที่คล้ายกันของเมธอดนี้คือ 
            method **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste**
            ที่เข้าถึงได้ผ่านคุณสมบัติ [`IPresentation.layout_slides`](/slides/python-net/th/aspose.slides/ipresentation/layout_slides).

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | เกิดขึ้นหากค่าที่ไม่รองรับของพารามิเตอร์ `layout_type` ถูกส่งเข้ามา. ชนิดของเลย์เอาต์ที่ยังไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นหากค่าชื่อเลย์เอาต์ `layout_name` ถูกใช้ไปแล้วใน <br/>            คอลเลกชันนี้ของเลย์เอาต์. |

### ดูเพิ่มเติม
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`MasterLayoutSlideCollection`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/th/aspose.slides/slidelayouttype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)