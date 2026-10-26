---
title: Portion()
second_title: مرجع API Aspose.Slides برای C++
description: "در Presentation هر ForEach::Portion را تکرار کنید."
type: docs
weight: 66
url: /fa/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) متد

تکرار هر [ForEach::Portion](./) در [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) برای تکرار بخش‌ها |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback که برای هر بخش فراخوانی می‌شود |

## توضیحات

بخش‌ها در تمام انواع اسلایدها - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) و [ForEach::LayoutSlide](../layoutslide/) تکرار خواهند شد

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## ForEach::Portion(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachPortionCallback) متد

تکرار هر [ForEach::Portion](./) در [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) برای تکرار بخش‌ها |
| includeNotes | **bool** | پرچمی که نشان می‌دهد آیا NotesSlides باید در پردازش گنجانده شود. |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback که برای هر بخش فراخوانی می‌شود |

## توضیحات

بخش‌ها در تمام انواع اسلایدها - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) و [NotesSlide](../../../aspose.slides/notesslide/) تکرار خواهند شد

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachPortionCallback](../foreachportioncallback/)
* کلاس [Presentation](../../../aspose.slides/presentation/)
* کلاس [ForEach](../)
* فضای‌نام [Aspose::Slides::LowCode](../../)
* کتابخانه [Aspose.Slides](../../../)