---
title: Paragraph()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "วนซ้ำแต่ละ ForEach::Paragraph ใน Presentation."
type: docs
weight: 53
url: /th/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach::Paragraph(System::SharedPtr\<Presentation\>, ForEach::ForEachParagraphCallback) method


วนซ้ำแต่ละ [ForEach::Paragraph](./) ใน [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, ForEach::ForEachParagraphCallback forEachParagraph)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) เพื่อวนซ้ำพารากราฟ |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละพารากราฟ |
## หมายเหตุ


รูปร่างจะถูกวนซ้ำในทุกประเภทของสไลด์ - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) และ [ForEach::LayoutSlide](../layoutslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, callback);
```

## ForEach::Paragraph(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachParagraphCallback) method


วนซ้ำแต่ละ [ForEach::Paragraph](./) ใน [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachParagraphCallback forEachParagraph)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) เพื่อวนซ้ำพารากราฟ |
| includeNotes | **bool** | แฟล็กที่ระบุว่า NotesSlides ควรจะถูกรวมในการประมวลผลหรือไม่ |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละพารากราฟ |
## หมายเหตุ


รูปร่างจะถูกวนซ้ำในทุกประเภทของสไลด์ - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) และ [NotesSlide](../../../aspose.slides/notesslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, true, callback);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachParagraphCallback](../foreachparagraphcallback/)
* คลาส [Presentation](../../../aspose.slides/presentation/)
* คลาส [ForEach](../)
* เนมสเปซ [Aspose::Slides::LowCode](../../)
* ไลบรารี [Aspose.Slides](../../../)