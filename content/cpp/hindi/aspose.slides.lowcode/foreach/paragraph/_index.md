---
title: Paragraph()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Presentation में प्रत्येक ForEach::Paragraph को दोहराएँ।"
type: docs
weight: 53
url: /hi/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach::Paragraph(System::SharedPtr\<Presentation\>, ForEach::ForEachParagraphCallback) विधि

प्रत्येक [ForEach::Paragraph](./) को [Presentation](../../../aspose.slides/presentation/) में दोहराएँ।

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, ForEach::ForEachParagraphCallback forEachParagraph)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) पैराग्राफ को दोहराने के लिए |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | प्रत्येक पैराग्राफ के लिए बुलाया जाने वाला कॉलबैक |

## टिप्पणियां

सभी प्रकार की स्लाइड्स में शेप्स दोहराए जाएंगे - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) और [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, callback);
```

## ForEach::Paragraph(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachParagraphCallback) विधि

प्रत्येक [ForEach::Paragraph](./) को [Presentation](../../../aspose.slides/presentation/) में दोहराएँ।

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachParagraphCallback forEachParagraph)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) पैराग्राफ को दोहराने के लिए |
| includeNotes | **bool** | फ़्लैग जो दर्शाता है कि NotesSlides को प्रोसेसिंग में शामिल किया जाना चाहिए या नहीं। |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | प्रत्येक पैराग्राफ के लिए बुलाया जाने वाला कॉलबैक |

## टिप्पणियां

सभी प्रकार की स्लाइड्स में शेप्स दोहराए जाएंगे - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) और [NotesSlide](../../../aspose.slides/notesslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, true, callback);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachParagraphCallback](../foreachparagraphcallback/)
* क्लास [Presentation](../../../aspose.slides/presentation/)
* क्लास [ForEach](../)
* नेमस्पेस [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)