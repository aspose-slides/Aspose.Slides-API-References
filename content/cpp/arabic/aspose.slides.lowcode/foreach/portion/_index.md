---
title: Portion()
second_title: "Aspose.Slides للـ C++ مرجع API"
description: "تكرار كل ForEach::Portion في Presentation."
type: docs
weight: 66
url: /ar/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) طريقة


تكرار كل [ForEach::Portion](./) في [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) لتكرار الأجزاء |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | دالة رد الاتصال التي سيتم استدعاؤها لكل جزء |
## ملاحظات


سيتم تكرار الأجزاء في جميع أنواع الشرائح - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) و [ForEach::LayoutSlide](../layoutslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## ForEach::Portion(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachPortionCallback) طريقة


تكرار كل [ForEach::Portion](./) في [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) لتكرار الأجزاء |
| includeNotes | **bool** | علامة تشير إلى ما إذا كان يجب تضمين NotesSlides في المعالجة. |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | دالة رد الاتصال التي سيتم استدعاؤها لكل جزء |
## ملاحظات


سيتم تكرار الأجزاء في جميع أنواع الشرائح - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) و [NotesSlide](../../../aspose.slides/notesslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachPortionCallback](../foreachportioncallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)