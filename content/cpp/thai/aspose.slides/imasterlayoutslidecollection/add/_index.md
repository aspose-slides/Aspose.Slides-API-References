---
title: Add()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มสไลด์เลเอาต์ใหม่ไปยังส่วนท้ายของคอลเลกชัน.
type: docs
weight: 27
url: /th/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) เมธอด


เพิ่มสไลด์เลเอาต์ใหม่ไปยังส่วนท้ายของคอลเลกชัน

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | ประเภทเลเอาต์สำหรับเลเอาต์ใหม่ ประเภทเลเอาต์ที่สนับสนุน: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ประเภทเลเอาต์อื่นที่ไม่ได้รับการสนับสนุนในขณะนี้: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | ชื่อสำหรับเลเอาต์ใหม่ หากชื่อที่ส่งเข้ามาใช้งานอยู่แล้วจะเกิด ArgumentException หากพารามิเตอร์เป็น null จะสร้างชื่อโดยอัตโนมัติตามประเภทเลเอาต์ที่ส่งเข้ามา (เช่น "Title Slide" หรือ "1_Title Slide", "2_..", ฯลฯ). |

### ค่าที่ส่งคืน

สไลด์ที่เพิ่ม

## หมายเหตุ

1) เพิ่มเลเอาต์สำหรับค่า [SlideLayoutType::Custom](../../slidelayouttype/) ของ *layoutType* ที่ไม่มีตัวแสดงตำแหน่งและไม่มีรูปทรง 2) ตรรกะของเมธอดนี้คือเมธอด [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) ที่เข้าถึงได้ผ่านคุณสมบัติ [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/)

## ดูเพิ่มเติม

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)