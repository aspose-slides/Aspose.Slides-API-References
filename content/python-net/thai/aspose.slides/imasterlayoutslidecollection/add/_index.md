---
title: add method
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
เพิ่มสไลด์เลเอาท์ใหม่ไปยังส่วนท้ายของคอลเลกชัน

### คืนค่า

สไลด์ที่เพิ่ม



```python
def add(self, layout_type, layout_name):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/th/aspose.slides/slidelayouttype) | ประเภทเลเอาท์สำหรับเลเอาท์ใหม่.<br/><br/>            ประเภทเลเอาท์ที่สนับสนุน: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            ประเภทเลเอาท์อื่นที่ไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | ชื่อสำหรับเลเอาท์ใหม่. หากชื่อที่ระบุอยู่แล้วจะทำให้เกิด ArgumentException.<br/><br/>            หากส่งพารามิเตอร์ None จะสร้างชื่อโดยอัตโนมัติตามประเภทเลเอาท์ที่ระบุ <br/><br/>            (เช่น "Title Slide" หรือ "1_Title Slide", "2_..", เป็นต้น). |

### หมายเหตุ

1) เลเอาท์ที่เพิ่มสำหรับค่า SlideLayoutType.Custom ของ `layout_type` จะไม่มีตัวแปรแทนและไม่มีรูปทรง.  
2) แบบจำลองของเมธอดนี้คือเมธอด **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** ที่เข้าถึงได้ผ่านคุณสมบัติ [`IPresentation.layout_slides`](/slides/python-net/th/aspose.slides/ipresentation/layout_slides).

### ข้อยกเว้น

| ข้อยกเว้น | รายละเอียด |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | เกิดขึ้นหากส่งค่า `layout_type` ที่ไม่รองรับ. ประเภทเลเอาท์ที่ไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นหากค่าชื่อเลเอาท์ `layout_name` ถูกใช้แล้วใน <br/>            คอลเลกชันของเลเอาท์นี้. |



### ดูเพิ่มเติม
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`IMasterLayoutSlideCollection`](/slides/python-net/th/aspose.slides/imasterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/th/aspose.slides/slidelayouttype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)