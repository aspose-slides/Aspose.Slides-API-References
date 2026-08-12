---
title: AddSectionZoomFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया Section Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।
type: docs
weight: 131
url: /hi/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) विधि

एक नया [Section](../../section/) ज़ूम फ्रेम बनाता है और उसे shape संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नई [Section](../../section/) ज़ूम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नई [Section](../../section/) ज़ूम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नई [Section](../../section/) ज़ूम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नई [Section](../../section/) ज़ूम फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) ज़ूम फ्रेम द्वारा संदर्भित [ISection](../../isection/); यह इस प्रस्तुति से संबंधित होना चाहिए और कम से कम एक स्लाइड शामिल करना चाहिए। |

### वापसी मान

नया बनाया गया [ISectionZoomFrame](../../isectionzoomframe/)।

## टिप्पणियाँ

यह उदाहरण एक [Section](../../section/) ज़ूम ऑब्जेक्ट को संग्रह के अंत में जोड़ने का प्रदर्शन करता है (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) विधि

एक नया [Section](../../section/) ज़ूम फ्रेम पूर्वनिर्धारित चित्र के साथ बनाता है और उसे shape संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नई [Section](../../section/) ज़ूम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नई [Section](../../section/) ज़ूम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नई [Section](../../section/) ज़ूम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नई [Section](../../section/) ज़ूम फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) ज़ूम फ्रेम द्वारा संदर्भित [ISection](../../isection/); यह इस प्रस्तुति से संबंधित होना चाहिए और कम से कम एक स्लाइड शामिल करना चाहिए। |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [Section](../../section/) ज़ूम फ्रेम के भीतर प्रदर्शित करने के लिए [IPPImage](../../ippimage/)। |

### वापसी मान

नया बनाया गया [ISectionZoomFrame](../../isectionzoomframe/)।

## टिप्पणियाँ

यह उदाहरण एक [Section](../../section/) ज़ूम ऑब्जेक्ट को संग्रह के अंत में जोड़ने का प्रदर्शन करता है (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)