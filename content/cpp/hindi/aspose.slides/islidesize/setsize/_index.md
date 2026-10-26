---
title: SetSize()
second_title: Aspose.Slides for C++ API संदर्भ
description: "स्लाइड आकार को प्रकार के अनुसार सेट करता है और मौजूदा सामग्री को स्केल करता है। SlideSizeType::Custom के अलावा कोई भी मान असाइन करने पर चयनित प्रकार के आधार पर ISlideSize::get_Size को समायोजित करता है, जबकि ISlideSize::get_Orientation को संरक्षित रखता है।"
type: docs
weight: 53
url: /hi/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) विधि

स्लाइड आकार को प्रकार द्वारा सेट करता है और मौजूदा सामग्री को स्केल करता है। [SlideSizeType::Custom](../../slidesizetype/) के अलावा कोई भी मान असाइन करने पर चयनित प्रकार के आधार पर [ISlideSize::get_Size](../get_size/) को समायोजित करता है, जबकि [ISlideSize::get_Orientation](../get_orientation/) को संरक्षित रखता है।

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | लागू करने के लिए पूर्वनिर्धारित स्लाइड आकार। |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | उपयोग करने के लिए सामग्री स्केलिंग मोड। |

## टिप्पणियाँ

[SlideSizeType::Custom](../../slidesizetype/) के अलावा कोई भी मान असाइन करने पर चयनित प्रकार के आधार पर [System::Drawing::Size](../../../system.drawing/size/) को समायोजित करता है, जबकि [Orientation](../../orientation/) को संरक्षित रखता है।

## ISlideSize::SetSize(float, float, SlideSizeScaleType) विधि

स्लाइड आयामों को स्पष्ट रूप से सेट करता है और मौजूदा सामग्री को स्केल करता है। यह [ISlideSize::get_Type](../get_type/) मान को [SlideSizeType::Custom](../../slidesizetype/) पर रीसेट करता है और [ISlideSize::get_Orientation](../get_orientation/) को सेट करता है।

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | **float** | नया स्लाइड चौड़ाई, बिंदुओं में। |
| height | **float** | नया स्लाइड ऊँचाई, बिंदुओं में। |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | उपयोग हेतु सामग्री स्केलिंग मोड। |

## टिप्पणियाँ

यह [ISlideSize::get_Type](../get_type/) प्रॉपर्टी को [SlideSizeType::Custom](../../slidesizetype/) पर रीसेट करता है और [Orientation](../../orientation/) को सेट करता है।

## देखें

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Class [ISlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)