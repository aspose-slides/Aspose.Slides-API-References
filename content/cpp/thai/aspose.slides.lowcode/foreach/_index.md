---
title: ForEach
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: แสดงถึงกลุ่มของเมธอดที่ออกแบบมาเพื่อวนซ้ำเหนือวัตถุโมเดล Presentation ต่าง ๆ เมธอดเหล่านี้อาจเป็นประโยชน์หากคุณต้องการวนซ้ำและเปลี่ยนรูปแบบหรือเนื้อหาของบางองค์ประกอบของ Presentation เช่น การเปลี่ยนรูปแบบของแต่ละส่วน
type: docs
weight: 40
url: /th/aspose.slides.lowcode/foreach/
---
## ForEach คลาส

แสดงถึงกลุ่มของเมธอดที่ออกแบบมาเพื่อวนซ้ำเหนือวัตถุโมเดล [Presentation](../../aspose.slides/presentation/) ต่าง ๆ เมธอดเหล่านี้อาจเป็นประโยชน์หากคุณต้องการวนซ้ำและเปลี่ยนรูปแบบหรือเนื้อหาของบางองค์ประกอบ [Presentation](../../aspose.slides/presentation/)' เช่น การเปลี่ยนรูปแบบของแต่ละส่วน

```cpp
class ForEach
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | วนซ้ำแต่ละ [ForEach::LayoutSlide](./layoutslide/) ใน [Presentation](../../aspose.slides/presentation/) |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | วนซ้ำแต่ละ [ForEach::MasterSlide](./masterslide/) ใน [Presentation](../../aspose.slides/presentation/) |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | วนซ้ำแต่ละ [ForEach::Paragraph](./paragraph/) ใน [Presentation](../../aspose.slides/presentation/) |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | วนซ้ำแต่ละ [ForEach::Paragraph](./paragraph/) ใน [Presentation](../../aspose.slides/presentation/) |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | วนซ้ำแต่ละ [ForEach::Portion](./portion/) ใน [Presentation](../../aspose.slides/presentation/) |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | วนซ้ำแต่ละ [ForEach::Portion](./portion/) ใน [Presentation](../../aspose.slides/presentation/) |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | วนซ้ำแต่ละ [ForEach::Shape](./shape/) ใน [Presentation](../../aspose.slides/presentation/) |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | วนซ้ำแต่ละ [ForEach::Shape](./shape/) ใน [Presentation](../../aspose.slides/presentation/) |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | วนซ้ำแต่ละ [ForEach::Shape](./shape/) ใน [BaseSlide](../../aspose.slides/baseslide/) |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | วนซ้ำแต่ละ [ForEach::Slide](./slide/) ใน [Presentation](../../aspose.slides/presentation/) |

## นิยามประเภท

| นิยามประเภท | คำอธิบาย |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [ForEach::Slide](./slide/) ใน [Presentation](../../aspose.slides/presentation/) |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [ForEach::MasterSlide](./masterslide/) ใน [Presentation](../../aspose.slides/presentation/) |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [ForEach::LayoutSlide](./layoutslide/) ใน [Presentation](../../aspose.slides/presentation/) |
| [ForEachShapeCallback](./foreachshapecallback/) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [ForEach::Shape](./shape/) ใน [Presentation](../../aspose.slides/presentation/) |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [ForEach::Paragraph](./paragraph/) บน [BaseSlide](../../aspose.slides/baseslide/) |
| [ForEachPortionCallback](./foreachportioncallback/) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [ForEach::Portion](./portion/) ใน [ForEach::Paragraph](./paragraph/) บน [BaseSlide](../../aspose.slides/baseslide/) |

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"Times New Roman"));
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(presentation, callback);

presentation->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* เนมสเปซ [Aspose::Slides::LowCode](../)
* ไลบรารี [Aspose.Slides](../../)