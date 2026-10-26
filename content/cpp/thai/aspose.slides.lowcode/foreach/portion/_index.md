---
title: Portion()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "วนซ้ำแต่ละ ForEach::Portion ใน Presentation."
type: docs
weight: 66
url: /th/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) เมธอด


วนซ้ำแต่ละ [ForEach::Portion](./) ใน [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) เพื่อวนซ้ำส่วน |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback ที่จะถูกเรียกสำหรับแต่ละส่วน |
## หมายเหตุ


ส่วนจะถูกวนซ้ำในสไลด์ทุกประเภท - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) และ [ForEach::LayoutSlide](../layoutslide/)


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## ForEach::Portion(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachPortionCallback) เมธอด


วนซ้ำแต่ละ [ForEach::Portion](./) ใน [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) เพื่อวนซ้ำส่วน |
| includeNotes | **bool** | แฟล็กที่ระบุว่า NotesSlides ควรจะรวมอยู่ในการประมวลผลหรือไม่ |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback ที่จะถูกเรียกสำหรับแต่ละส่วน |
## หมายเหตุ


ส่วนจะถูกวนซ้ำในสไลด์ทุกประเภท - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) และ [NotesSlide](../../../aspose.slides/notesslide/)


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* กำหนดชนิด [ForEachPortionCallback](../foreachportioncallback/)
* คลาส [Presentation](../../../aspose.slides/presentation/)
* คลาส [ForEach](../)
* เนมสเปซ [Aspose::Slides::LowCode](../../)
* ไลบรารี [Aspose.Slides](../../../)