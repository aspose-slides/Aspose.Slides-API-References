---
title: AddZoomFrame()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक नया ज़ूम फ़्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।
type: docs
weight: 92
url: /hi/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) विधि

एक नया ज़ूम फ़्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए ज़ूम फ़्रेम का x-निर्देशांक, बिंदुओं में। |
| y | **float** | नए ज़ूम फ़्रेम का y-निर्देशांक, बिंदुओं में। |
| width | **float** | नए ज़ूम फ़्रेम की चौड़ाई, बिंदुओं में। |
| height | **float** | नए ज़ूम फ़्रेम की ऊँचाई, बिंदुओं में। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom फ़्रेम द्वारा संदर्भित [ISlide](../../islide/); यह प्रस्तुति का भाग होना चाहिए। |

### रिटर्न मान

नया बनाया गया [IZoomFrame](../../izoomframe/)।

## टिप्पणियाँ

यह उदाहरण एक ज़ूम ऑब्जेक्ट को संग्रह के अंत में जोड़ने को प्रदर्शित करता है (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो स्लाइड हैं):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) विधि

एक नया ज़ूम फ़्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए ज़ूम फ़्रेम का x-निर्देशांक, बिंदुओं में। |
| y | **float** | नए ज़ूम फ़्रेम का y-निर्देशांक, बिंदुओं में। |
| width | **float** | नए ज़ूम फ़्रेम की चौड़ाई, बिंदुओं में। |
| height | **float** | नए ज़ूम फ़्रेम की ऊँचाई, बिंदुओं में। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom फ़्रेम द्वारा संदर्भित [ISlide](../../islide/); यह प्रस्तुति का भाग होना चाहिए। |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | संदर्भित स्लाइड [IPPImage](../../ippimage/) के लिए छवि। |

### रिटर्न मान

नया बनाया गया [IZoomFrame](../../izoomframe/)।

## टिप्पणियाँ

यह उदाहरण एक ज़ूम ऑब्जेक्ट को संग्रह के अंत में जोड़ने को प्रदर्शित करता है (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो स्लाइड हैं):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)