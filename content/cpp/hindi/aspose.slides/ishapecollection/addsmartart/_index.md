---
title: AddSmartArt()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक SmartArt डायग्राम बनाता है और इसे shape collection के अंत में जोड़ता है।
type: docs
weight: 40
url: /hi/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) method

एक [SmartArt](../../../aspose.slides.smartart/) डायग्राम बनाता है और इसे shape collection के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | **float** | डायग्राम के फ्रेम का x-निर्देशांक, बिंदुओं में। |
| y | **float** | डायग्राम के फ्रेम का y-निर्देशांक, बिंदुओं में। |
| width | **float** | डायग्राम के फ्रेम की चौड़ाई, बिंदुओं में। |
| height | **float** | डायग्राम के फ्रेम की ऊँचाई, बिंदुओं में। |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | [SmartArt](../../../aspose.slides.smartart/) लेआउट प्रकार। |

### रिटर्न वैल्यू

नया बनाया गया [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/)।

## टिप्पणियाँ

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## देखें

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)