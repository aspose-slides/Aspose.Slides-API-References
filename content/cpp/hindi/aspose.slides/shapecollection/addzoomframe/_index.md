---
title: AddZoomFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया Zoom फ्रेम बनाता है और इसे shape collection के अंत में जोड़ता है।
type: docs
weight: 105
url: /hi/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) विधि

एक नया Zoom फ्रेम बनाता है और इसे shape collection के अंत में जोड़ता है।

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../islide/); यह प्रस्तुतिकरण का हिस्सा होना चाहिए। |

### वापसी मान

नया बनाया गया [IZoomFrame](../../izoomframe/)।

## टिप्पणी

यह उदाहरण संग्रह के अंत में Zoom ऑब्जेक्ट जोड़ने को दर्शाता है (मान लीजिए \"Presentation.pptx\" प्रस्तुति में कम से कम दो स्लाइड हैं): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) विधि

एक नया Zoom फ्रेम बनाता है और इसे shape collection के अंत में जोड़ता है।

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../islide/); यह प्रस्तुतिकरण का हिस्सा होना चाहिए। |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | संदर्भित स्लाइड [IPPImage](../../ippimage/) के लिए छवि। |

### वापसी मान

नया बनाया गया [IZoomFrame](../../izoomframe/)।

## टिप्पणी

यह उदाहरण संग्रह के अंत में Zoom ऑब्जेक्ट जोड़ने को दर्शाता है (मान लीजिए \"Presentation.pptx\" प्रस्तुति में कम से कम दो स्लाइड हैं): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IZoomFrame](../../izoomframe/)
* क्लास [ISlide](../../islide/)
* क्लास [ShapeCollection](../)
* क्लास [IPPImage](../../ippimage/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)