---
title: Add()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มสไลด์เลเอาต์ใหม่ไปยังท้ายของคอลเลกชัน.
type: docs
weight: 27
url: /th/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) เมธอด

เพิ่มสไลด์เลเอาต์ใหม่ไปยังท้ายของคอลเลกชัน。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | ประเภทเลเอาต์สำหรับเลเอาต์ใหม่ ประเภทเลเอาต์ที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ประเภทเลเอาต์อื่น ๆ ที่ไม่ได้รับการสนับสนุนในขณะนี้: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | ชื่อสำหรับเลเอาต์ใหม่ หากชื่อที่ส่งเข้ามาใช้อยู่แล้วจะทำให้เกิด ArgumentException หากพารามิเตอร์เป็น null จะสร้างชื่อโดยอัตโนมัติตามประเภทเลเอาต์ที่ส่งเข้ามา (เช่น "Title Slide" หรือ "1_Title Slide", "2_..", เป็นต้น). |

### ค่าที่คืนกลับ

สไลด์ที่เพิ่ม

## หมายเหตุ

1) เลเอาต์ที่เพิ่มสำหรับค่า [SlideLayoutType::Custom](../../slidelayouttype/) ของ *layoutType* ไม่มีตัวแทนและไม่มีรูปทรง 2) คล้ายกับเมธอดนี้คือเมธอด [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) ที่เข้าถึงได้ด้วยพรอพเพอร์ตี [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## ดูเพิ่มเติม

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ILayoutSlide](../../ilayoutslide/)
* คลาส [String](../../../system/string/)
* คลาส [MasterLayoutSlideCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)