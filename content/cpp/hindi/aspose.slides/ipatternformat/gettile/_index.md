---
title: GetTile()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट रंगों के साथ पैटर्न भराव के लिए टाइल छवि बनाता है।
type: docs
weight: 53
url: /hi/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) विधि

निर्दिष्ट रंगों के साथ पैटर्न भराव के लिए टाइल छवि बनाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | पैटर्न के लिए पृष्ठभूमि [System::Drawing::Color](../../../system.drawing/color/)। |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | पैटर्न के लिए अग्रभूमि [System::Drawing::Color](../../../system.drawing/color/)। |

### वापसी मान

टाइल [System::Drawing::Bitmap](../../../system.drawing/bitmap/)।

## IPatternFormat::GetTile(System::Drawing::Color) विधि

पैटर्न भराव के लिए टाइल छवि बनाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | डिफ़ॉल्ट [System::Drawing::Color](../../../system.drawing/color/), जो ShapeEx के StyleEx ऑब्जेक्ट में परिभाषित है। फ़िल के रंग इस पर निर्भर हो सकते हैं। |

### वापसी मान

टाइल [System::Drawing::Bitmap](../../../system.drawing/bitmap/)।

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IImage](../../iimage/)
* क्लास [Color](../../../system.drawing/color/)
* क्लास [IPatternFormat](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)