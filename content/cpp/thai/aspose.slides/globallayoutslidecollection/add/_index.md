---
title: Add()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มสไลด์เค้าโครงใหม่ไปยังงานนำเสนอ
type: docs
weight: 14
url: /th/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) เมธอด

เพิ่มสไลด์เค้าโครงใหม่ไปยังงานนำเสนอ

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | สไลด์มาสเตอร์สำหรับเค้าโครงใหม่ |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | ประเภทเค้าโครงสำหรับเค้าโครงใหม่ รองรับประเภทเค้าโครง: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ประเภทเค้าโครงอื่น ๆ ยังไม่รองรับ: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject |
| layoutName | [System::String](../../../system/string/) | ชื่อสำหรับเค้าโครงใหม่ หากชื่อที่ส่งเข้ามาใช้แล้วจะทำให้เกิด ArgumentException หากพารามิเตอร์เป็น null จะสร้างชื่อโดยอัตโนมัติตามประเภทเค้าโครงที่ส่ง (เช่น \"Title Slide\" หรือ \"1_Title Slide\", \"2_..\" เป็นต้น) |

### ค่าที่คืน

สไลด์ที่เพิ่ม

## หมายเหตุ

1) เพิ่มเค้าโครงสำหรับค่า [SlideLayoutType::Custom](../../slidelayouttype/) ของ *layoutType* ที่ไม่มีตัวแปรแทนและไม่มีรูปร่าง 2) วิธีการที่เป็นแบบเดียวกันของเมธอดนี้คือเมธอด [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) ซึ่งเข้าถึงได้ด้วย property [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/)

## ดูเพิ่มเติม

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Class [String](../../../system/string/)
* Class [GlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)