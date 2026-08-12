---
title: Portion()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "Presentation में प्रत्येक ForEach::Portion को इटररेट करें।"
type: docs
weight: 66
url: /hi/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) विधि

प्रत्येक [ForEach::Portion](./) को [Presentation](../../../aspose.slides/presentation/) में इटररेट करें।

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) भागों को इटररेट करने के लिए |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback जो प्रत्येक भाग के लिए कॉल किया जाएगा |

## टिप्पणियाँ

सभी प्रकार की स्लाइड्स - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) और [ForEach::LayoutSlide](../layoutslide/) में भागों को इटररेट किया जाएगा।

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## ForEach::Portion(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachPortionCallback) विधि

प्रत्येक [ForEach::Portion](./) को [Presentation](../../../aspose.slides/presentation/) में इटररेट करें।

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) भागों को इटररेट करने के लिए |
| includeNotes | **bool** | Flag जो संकेत करता है कि NotesSlides को प्रोसेसिंग में शामिल किया जाना चाहिए। |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback जो प्रत्येक भाग के लिए कॉल किया जाएगा |

## टिप्पणियाँ

सभी प्रकार की स्लाइड्स - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) और [NotesSlide](../../../aspose.slides/notesslide/) में भागों को इटररेट किया जाएगा।

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachPortionCallback](../foreachportioncallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)