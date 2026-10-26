---
title: GetTile()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट रंगों के साथ पैटर्न फ़िल के लिए टाइल इमेज बनाता है।
type: docs
weight: 53
url: /hi/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) मेथड

निर्दिष्ट रंगों के साथ पैटर्न फ़िल के लिए टाइल इमेज बनाता है।

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | पैटर्न के लिए बैकग्राउंड [System::Drawing::Color](../../../system.drawing/color/)। |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | पैटर्न के लिए फ़ोरग्राउंड [System::Drawing::Color](../../../system.drawing/color/)। |

### Return Value

टाइल [IImage](../../iimage/)।

## PatternFormat::GetTile(System::Drawing::Color) मेथड

पैटर्न फ़िल के लिए टाइल इमेज बनाता है।

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | डिफ़ॉल्ट [System::Drawing::Color](../../../system.drawing/color/) |

### Return Value

टाइल [IImage](../../iimage/)।

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IImage](../../iimage/)
* क्लास [Color](../../../system.drawing/color/)
* क्लास [PatternFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)