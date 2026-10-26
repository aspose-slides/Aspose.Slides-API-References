---
title: AddSmartArt()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक SmartArt डायग्राम बनाता है और उसे shape collection के अंत में जोड़ता है।
type: docs
weight: 79
url: /hi/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) विधि

एक [SmartArt](../../../aspose.slides.smartart/) आरेख बनाता है और उसे शेप संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | डायग्राम के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | डायग्राम के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | डायग्राम के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | डायग्राम के फ्रेम की ऊंचाई, पॉइंट्स में। |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | [SmartArt](../../../aspose.slides.smartart/) लेआउट प्रकार। |

### रिटर्न मान

नया निर्मित [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/)।

## टिप्पणियाँ



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## संबंधित

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)