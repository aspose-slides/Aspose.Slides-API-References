---
title: Add()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เพิ่มสไลด์เค้าโครงใหม่ไปยังการนำเสนอ.
type: docs
weight: 14
url: /th/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) method

เพิ่มสไลด์เค้าโครงใหม่ไปยังการนำเสนอ.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | สไลด์มาสเตอร์สำหรับเค้าโครงใหม่ |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | ประเภทเค้าโครงสำหรับเค้าโครงใหม่ ประเภทเค้าโครงที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ประเภทเค้าโครงอื่น ๆ ที่ไม่ได้รองรับในขณะนี้: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject |
| layoutName | [System::String](../../../system/string/) | ชื่อสำหรับเค้าโครงใหม่ หากชื่อที่ส่งเข้ามาเป็นชื่อที่ใช้อยู่แล้วจะเกิด ArgumentException หากส่งพารามิเตอร์ null จะสร้างชื่อโดยอัตโนมัติตามประเภทเค้าโครงที่ส่ง (เช่น "Title Slide" หรือ "1_Title Slide", "2_..", เป็นต้น) |

### ค่าที่คืนกลับ

สไลด์ที่เพิ่ม

## หมายเหตุ

1) เค้าโครงที่เพิ่มสำหรับค่า [SlideLayoutType::Custom](../../slidelayouttype/) ของ *layoutType* ไม่มีตำแหน่งเก็บข้อมูลและไม่มีรูปทรงใด ๆ 2) วิธีการที่คล้ายกับเมธอดนี้คือเมธอด [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) ที่เข้าถึงได้ผ่านคุณสมบัติ [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/)

## ดูเพิ่มเติม

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ILayoutSlide](../../ilayoutslide/)
* คลาส [IMasterSlide](../../imasterslide/)
* คลาส [String](../../../system/string/)
* คลาส [IGlobalLayoutSlideCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)