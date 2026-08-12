---
title: SetSize()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्लाइड का आकार प्रकार द्वारा सेट करता है और मौजूदा सामग्री को स्केल करता है।
type: docs
weight: 53
url: /hi/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) विधि

Sets the slide size by type and scales existing content.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | लागू करने के लिए पूर्वनिर्धारित स्लाइड आकार। |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | उपयोग करने के लिए सामग्री स्केलिंग मोड। |
## टिप्पणी

[SlideSizeType::Custom](../../slidesizetype/) के अलावा कोई भी मान असाइन करने पर चयनित प्रकार के आधार पर [SlideSize::get_Size](../get_size/) समायोजित होता है, जबकि [SlideSize::get_Orientation](../get_orientation/) को संरक्षित रखा जाता है। 

## SlideSize::SetSize(float, float, SlideSizeScaleType) विधि

Sets the slide dimensions explicitly and scales existing content.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | **float** | नया स्लाइड चौड़ाई, पॉइंट में। |
| height | **float** | नया स्लाइड ऊँचाई, पॉइंट में। |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | उपयोग करने के लिए सामग्री स्केलिंग मोड। |
## टिप्पणी

यह [SlideSize::get_Type](../get_type/) प्रॉपर्टी को [SlideSizeType::Custom](../../slidesizetype/) पर रीसेट करता है और [Orientation](../../orientation/) को सेट करता है। 

## देखें

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* क्लास [SlideSize](../)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)