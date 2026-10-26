---
title: Insert()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทรกสไลด์เลย์เอาต์ใหม่ไปยังตำแหน่งที่ระบุของคอลเลกชัน
type: docs
weight: 40
url: /th/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) method

แทรกสไลด์เลย์เอาต์ใหม่ไปยังตำแหน่งที่ระบุของคอลเลกชัน

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของสไลด์ใหม่ |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | ประเภทเลย์เอาต์สำหรับเลย์เอาต์ใหม่ ประเภทเลย์เอาต์ที่สนับสนุน: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ปัจจุบันไม่สนับสนุนประเภทเลย์เอาต์อื่น: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | ชื่อสำหรับเลย์เอาต์ใหม่ หากชื่อที่ส่งเข้ามาใช้แล้วจะเกิด ArgumentException หากส่งพารามิเตอร์ null จะสร้างชื่อโดยอัตโนมัติตามประเภทเลย์เอาต์ที่ส่งเข้ามา (เช่น "Title Slide" หรือ "1_Title Slide", "2_..", เป็นต้น) |

### ค่าที่ส่งกลับ

สไลด์ที่แทรก

## หมายเหตุ



เลเอาต์ที่แทรกสำหรับค่า [SlideLayoutType::Custom](../../slidelayouttype/) ของ *layoutType* ไม่มีตัวแสดงตำแหน่งและไม่มีรูปร่าง

## ดูเพิ่มเติม

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ILayoutSlide](../../ilayoutslide/)
* คลาส [String](../../../system/string/)
* คลาส [MasterLayoutSlideCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)