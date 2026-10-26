---
title: Insert()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: แทรกสไลด์เค้าโครงใหม่ไปยังตำแหน่งที่ระบุของคอลเลกชัน.
type: docs
weight: 40
url: /th/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) method

แทรกสไลด์เค้าโครงใหม่ไปยังตำแหน่งที่ระบุของคอลเลกชัน

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของสไลด์ใหม่ |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | ประเภทเค้าโครงสำหรับเค้าโครงใหม่ ประเภทเค้าโครงที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ประเภทเค้าโครงอื่น ๆ ที่ไม่รองรับในขณะนี้: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject |
| layoutName | [System::String](../../../system/string/) | ชื่อสำหรับเค้าโครงใหม่ หากชื่อที่ส่งเข้ามาใช้งานแล้วจะทำให้เกิด ArgumentException หากส่งพารามิเตอร์เป็น null ชื่อจะถูกสร้างโดยอัตโนมัติตามประเภทเค้าโครงที่ส่งเข้ามา (ตัวอย่างเช่น "Title Slide" หรือ "1_Title Slide", "2_..", เป็นต้น) |

### ค่าที่ส่งคืน

สไลด์ที่ถูกแทรก

## หมายเหตุ

เค้าโครงที่แทรกสำหรับค่าของ [SlideLayoutType::Custom](../../slidelayouttype/) ของ *layoutType*  ไม่มีตัวยึดตำแหน่งและไม่มีรูปร่าง

## ดูเพิ่มเติม

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ILayoutSlide](../../ilayoutslide/)
* คลาส [String](../../../system/string/)
* คลาส [IMasterLayoutSlideCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)