---
title: Portion()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Επανάληψη κάθε ForEach::Portion στην Παρουσίαση."
type: docs
weight: 66
url: /el/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) μέθοδος


Επανάληψη κάθε [ForEach::Portion](./) στο [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) για επανάληψη τμημάτων |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback που θα κληθεί για κάθε τμήμα |
## Παρατηρήσεις


Τα τμήματα θα επαναληφθούν σε όλους τους τύπους διαφανειών - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) και [ForEach::LayoutSlide](../layoutslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## ForEach::Portion(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachPortionCallback) μέθοδος


Επανάληψη κάθε [ForEach::Portion](./) στο [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) για επανάληψη τμημάτων |
| includeNotes | **bool** | Σημαία που δείχνει εάν τα NotesSlides πρέπει να συμπεριληφθούν στην επεξεργασία. |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback που θα κληθεί για κάθε τμήμα |
## Παρατηρήσεις


Τα τμήματα θα επαναληφθούν σε όλους τους τύπους διαφανειών - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) και [NotesSlide](../../../aspose.slides/notesslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachPortionCallback](../foreachportioncallback/)
* Κλάση [Presentation](../../../aspose.slides/presentation/)
* Κλάση [ForEach](../)
* Χώρος ονομάτων [Aspose::Slides::LowCode](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)