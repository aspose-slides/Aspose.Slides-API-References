---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट इंडेक्स पर नया सेक्शन ज़ूम फ्रेम बनाता है और उसे shape collection में डालता है।
type: docs
weight: 144
url: /hi/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) मेथड

निर्दिष्ट इंडेक्स पर एक नया [Section](../../section/) Zoom फ़्रेम बनाता है और उसे shape collection में डालता है।

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | शून्य-आधारित इंडेक्स जहाँ [Section](../../section/) Zoom फ्रेम डालनी है। |
| x | **float** | नए [Section](../../section/) Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए [Section](../../section/) Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए [Section](../../section/) Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए [Section](../../section/) Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom फ्रेम द्वारा संदर्भित [ISection](../../isection/); यह प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड रखनी चाहिए। |

### वापसी मान

नव निर्मित [ISectionZoomFrame](../../isectionzoomframe/)।

## टिप्पणियाँ

यह उदाहरण निर्दिष्ट इंडेक्स पर एक संग्रह में [Section](../../section/) Zoom ऑब्जेक्ट के निर्माण और सम्मिलन को दर्शाता है (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) मेथड

पूर्वनिर्धारित इमेज के साथ एक नया [Section](../../section/) Zoom फ्रेम बनाता है और उसे निर्दिष्ट इंडेक्स पर shape collection में डालता है।

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | शून्य-आधारित इंडेक्स जहाँ [Section](../../section/) Zoom फ्रेम डालनी है। |
| x | **float** | नए [Section](../../section/) Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए [Section](../../section/) Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए [Section](../../section/) Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए [Section](../../section/) Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom फ्रेम द्वारा संदर्भित [ISection](../../isection/); यह प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड रखनी चाहिए। |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [Section](../../section/) Zoom फ्रेम के भीतर प्रदर्शित करने वाली इमेज। |

### वापसी मान

नव निर्मित [ISectionZoomFrame](../../isectionzoomframe/)।

## टिप्पणियाँ

यह उदाहरण निर्दिष्ट इंडेक्स पर एक संग्रह में [Section](../../section/) Zoom ऑब्जेक्ट के निर्माण और सम्मिलन को दर्शाता है (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISectionZoomFrame](../../isectionzoomframe/)
* क्लास [ISection](../../isection/)
* क्लास [ShapeCollection](../)
* क्लास [IPPImage](../../ippimage/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)