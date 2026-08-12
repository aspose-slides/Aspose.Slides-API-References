---
title: InsertZoomFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया Zoom फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर shape collection में सम्मिलित करता है।
type: docs
weight: 105
url: /hi/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) विधि

एक नया Zoom फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर shape collection में सम्मिलित करता है।

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | Zoom फ्रेम डालने के लिए शून्य-आधारित अनुक्रमणिका। |
| x | **float** | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../islide/)। |

### रिटर्न मान

नया बनाया गया [IZoomFrame](../../izoomframe/)।

## टिप्पणियाँ

यह उदाहरण संग्रह में निर्दिष्ट अनुक्रमणिका पर Zoom ऑब्जेक्ट बनाने और सम्मिलित करने को दर्शाता है (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो स्लाइड हैं): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) विधि

एक पूर्वनिर्धारित छवि के साथ नया Zoom फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर shape collection में सम्मिलित करता है।

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | Zoom फ्रेम डालने के लिए शून्य-आधारित अनुक्रमणिका। |
| x | **float** | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../islide/)। |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | संदर्भित स्लाइड [IPPImage](../../ippimage/) के लिए छवि। |

### रिटर्न मान

नया बनाया गया [IZoomFrame](../../izoomframe/)।

## टिप्पणियाँ

यह उदाहरण संग्रह में निर्दिष्ट अनुक्रमणिका पर Zoom ऑब्जेक्ट बनाने और सम्मिलित करने को दर्शाता है (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो स्लाइड हैं): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IZoomFrame](../../izoomframe/)
* क्लास [ISlide](../../islide/)
* क्लास [IShapeCollection](../)
* क्लास [IPPImage](../../ippimage/)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)