---
title: GetTile()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट रंगों के साथ पैटर्न फ़िल के लिए टाइल इमेज बनाता है।
type: docs
weight: 53
url: /hi/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) method

निर्दिष्ट रंगों के साथ पैटर्न फ़िल के लिए टाइल इमेज बनाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | पैटर्न के लिए बैकग्राउंड [System::Drawing::Color](../../../system.drawing/color/)। |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | पैटर्न के लिए फोरग्राउंड [System::Drawing::Color](../../../system.drawing/color/)। |

### रिटर्न वैल्यू

टाइल [IImage](../../iimage/)।

## IPatternFormat::GetTile(System::Drawing::Color) method

पैटर्न फ़िल के लिए टाइल इमेज बनाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | डिफॉल्ट [System::Drawing::Color](../../../system.drawing/color/), जो ShapeEx के StyleEx ऑब्जेक्ट में परिभाषित है। Fill के रंग इस पर निर्भर कर सकते हैं। |

### रिटर्न वैल्यू

टाइल [IImage](../../iimage/)।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Color](../../../system.drawing/color/)
* Class [IPatternFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)