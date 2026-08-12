---
title: ForEach
second_title: Aspose.Slides for C++ API संदर्भ
description: विभिन्न Presentation मॉडल ऑब्जेक्ट्स पर दोहराने के लिए उद्देशित विधियों का समूह दर्शाता है। यदि आपको कुछ Presentation तत्वों का फ़ॉर्मेट या सामग्री बदलनी है, जैसे प्रत्येक भाग का फ़ॉर्मेट बदलना, तो ये विधियाँ उपयोगी हो सकती हैं।
type: docs
weight: 40
url: /hi/aspose.slides.lowcode/foreach/
---
## ForEach वर्ग

[Presentation](../../aspose.slides/presentation/) मॉडल ऑब्जेक्ट्स पर दोहराने के लिए उद्देशित विधियों का समूह दर्शाता है। यदि आपको कुछ [Presentation](../../aspose.slides/presentation/) तत्वों का फॉर्मेट या सामग्री बदलनी है, जैसे प्रत्येक भाग का फॉर्मेट बदलना, तो ये विधियाँ उपयोगी हो सकती हैं।

```cpp
class ForEach
```

## विधियां

| विधि | विवरण |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | [Presentation](../../aspose.slides/presentation/) में प्रत्येक [ForEach::LayoutSlide](./layoutslide/) को दोहराएँ। |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | [Presentation](../../aspose.slides/presentation/) में प्रत्येक [ForEach::MasterSlide](./masterslide/) को दोहराएँ। |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | [Presentation](../../aspose.slides/presentation/) में प्रत्येक [ForEach::Paragraph](./paragraph/) को दोहराएँ। |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | [Presentation](../../aspose.slides/presentation/) में प्रत्येक [ForEach::Paragraph](./paragraph/) को दोहराएँ। |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | [Presentation](../../aspose.slides/presentation/) में प्रत्येक [ForEach::Portion](./portion/) को दोहराएँ। |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | [Presentation](../../aspose.slides/presentation/) में प्रत्येक [ForEach::Portion](./portion/) को दोहराएँ। |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | [Presentation](../../aspose.slides/presentation/) में प्रत्येक [ForEach::Shape](./shape/) को दोहराएँ। |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | [Presentation](../../aspose.slides/presentation/) में प्रत्येक [ForEach::Shape](./shape/) को दोहराएँ। |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | [BaseSlide](../../aspose.slides/baseslide/) में प्रत्येक [ForEach::Shape](./shape/) को दोहराएँ। |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | [Presentation](../../aspose.slides/presentation/) में प्रत्येक [ForEach::Slide](./slide/) को दोहराएँ। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | [Presentation](../../aspose.slides/presentation/) में प्रत्येक [ForEach::Slide](./slide/) के लिए कॉलबैक को बुलाया जाएगा। |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | [Presentation](../../aspose.slides/presentation/) में प्रत्येक [ForEach::MasterSlide](./masterslide/) के लिए कॉलबैक को बुलाया जाएगा। |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | [Presentation](../../aspose.slides/presentation/) में प्रत्येक [ForEach::LayoutSlide](./layoutslide/) के लिए कॉलबैक को बुलाया जाएगा। |
| [ForEachShapeCallback](./foreachshapecallback/) | [Presentation](../../aspose.slides/presentation/) में प्रत्येक [ForEach::Shape](./shape/) के लिए कॉलबैक को बुलाया जाएगा। |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | [BaseSlide](../../aspose.slides/baseslide/) पर प्रत्येक [ForEach::Paragraph](./paragraph/) के लिए कॉलबैक को बुलाया जाएगा। |
| [ForEachPortionCallback](./foreachportioncallback/) | [BaseSlide](../../aspose.slides/baseslide/) पर [ForEach::Paragraph](./paragraph/) में प्रत्येक [ForEach::Portion](./portion/) के लिए कॉलबैक को बुलाया जाएगा। |

## टिप्पणी



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

## देखें भी

* नामस्थल [Aspose::Slides::LowCode](../)
* लाइब्रेरी [Aspose.Slides](../../)