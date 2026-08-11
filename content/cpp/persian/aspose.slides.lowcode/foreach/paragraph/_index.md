---
title: Paragraph()
second_title: "Aspose.Slides برای مرجع API C++"
description: "هر ForEach::Paragraph را در Presentation تکرار کنید."
type: docs
weight: 53
url: /fa/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach::Paragraph(System::SharedPtr\<Presentation\>, ForEach::ForEachParagraphCallback) method


هر [ForEach::Paragraph](./) را در [Presentation](../../../aspose.slides/presentation/) تکرار کنید.

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, ForEach::ForEachParagraphCallback forEachParagraph)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) برای تکرار پاراگراف‌ها |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | تابعی که برای هر پاراگراف فراخوانی می‌شود |
## ملاحظات


اشکال در تمام انواع اسلایدها - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) و [ForEach::LayoutSlide](../layoutslide/) تکرار می‌شوند



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


هر [ForEach::Paragraph](./) را در [Presentation](../../../aspose.slides/presentation/) تکرار کنید.

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachParagraphCallback forEachParagraph)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) برای تکرار پاراگراف‌ها |
| includeNotes | **bool** | پرچمی که نشان می‌دهد آیا NotesSlides باید در پردازش گنجانده شود یا نه. |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | تابعی که برای هر پاراگراف فراخوانی می‌شود |
## ملاحظات


اشکال در تمام انواع اسلایدها - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) و [NotesSlide](../../../aspose.slides/notesslide/) تکرار می‌شوند



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, true, callback);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachParagraphCallback](../foreachparagraphcallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)