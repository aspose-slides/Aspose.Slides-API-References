---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट अनुक्रमांक पर नई Section Zoom फ्रेम बनाता है और उसे shape संग्रह में सम्मिलित करता है।
type: docs
weight: 131
url: /hi/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) method

निर्दिष्ट अनुक्रमांक पर नई [Section](../../section/) Zoom फ़्रेम बनाता है और उसे shape संग्रह में सम्मिलित करता है।

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | जिस शून्य-आधारित अनुक्रमांक पर [Section](../../section/) Zoom फ़्रेम सम्मिलित करनी है। |
| x | **float** | नए [Section](../../section/) Zoom फ़्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए [Section](../../section/) Zoom फ़्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए [Section](../../section/) Zoom फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए [Section](../../section/) Zoom फ़्रेम की ऊँचाई, पॉइंट्स में। |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) जिसका उल्लेख [Section](../../section/) Zoom फ़्रेम द्वारा किया गया है; यह प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड होना चाहिए। |

### रिटर्न मान

नव निर्मित [ISectionZoomFrame](../../isectionzoomframe/)।

## टिप्पणी

यह उदाहरण एक संग्रह में निर्दिष्ट अनुक्रमांक पर [Section](../../section/) Zoom ऑब्जेक्ट बनाने और सम्मिलित करने का प्रदर्शन करता है (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method

निर्दिष्ट अनुक्रमांक पर पूर्वनिर्धारित छवि के साथ नई [Section](../../section/) Zoom फ़्रेम बनाता है और उसे shape संग्रह में सम्मिलित करता है।

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | जिस शून्य-आधारित अनुक्रमांक पर [Section](../../section/) Zoom फ़्रेम सम्मिलित करनी है। |
| x | **float** | नए [Section](../../section/) Zoom फ़्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए [Section](../../section/) Zoom फ़्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए [Section](../../section/) Zoom फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए [Section](../../section/) Zoom फ़्रेम की ऊँचाई, पॉइंट्स में। |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) जिसका उल्लेख [Section](../../section/) Zoom फ़्रेम द्वारा किया गया है; यह प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड होना चाहिए। |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [Section](../../section/) Zoom फ़्रेम के भीतर प्रदर्शित करने की छवि। |

### रिटर्न मान

नव निर्मित [ISectionZoomFrame](../../isectionzoomframe/)।

## टिप्पणी

यह उदाहरण एक संग्रह में निर्दिष्ट अनुक्रमांक पर [Section](../../section/) Zoom ऑब्जेक्ट बनाने और सम्मिलित करने का प्रदर्शन करता है (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)