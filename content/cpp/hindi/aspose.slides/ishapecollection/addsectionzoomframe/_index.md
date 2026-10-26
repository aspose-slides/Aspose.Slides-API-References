---
title: AddSectionZoomFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया Section Zoom फ्रेम बनाता है और इसे shape collection के अंत में जोड़ता है।
type: docs
weight: 118
url: /hi/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) विधि

एक नया [Section](../../section/) Zoom फ़्रेम बनाता है और इसे shape collection के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | नए [Section](../../section/) Zoom फ़्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए [Section](../../section/) Zoom फ़्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए [Section](../../section/) Zoom फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए [Section](../../section/) Zoom फ़्रेम की ऊँचाई, पॉइंट्स में। |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) जिसका संदर्भ [Section](../../section/) Zoom फ़्रेम द्वारा दिया गया है; यह प्रस्तुति से संबंधित होना चाहिए और कम से कम एक स्लाइड शामिल करना चाहिए। |

### रिटर्न मान

नए बनाए गए [ISectionZoomFrame](../../isectionzoomframe/)।

## टिप्पणी

यह उदाहरण एक [Section](../../section/) Zoom ऑब्जेक्ट को संग्रह के अंत में जोड़ने को दर्शाता है (मान लें कि \"Presentation.pptx\" प्रस्तुति में कम से कम दो सेक्शन हैं): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) विधि

एक नया [Section](../../section/) Zoom फ़्रेम पूर्वनिर्धारित चित्र के साथ बनाता है और इसे shape collection के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | नए [Section](../../section/) Zoom फ़्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए [Section](../../section/) Zoom फ़्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए [Section](../../section/) Zoom फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए [Section](../../section/) Zoom फ़्रेम की ऊँचाई, पॉइंट्स में। |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) जिसका संदर्भ [Section](../../section/) Zoom फ़्रेम द्वारा दिया गया है; यह प्रस्तुति से संबंधित होना चाहिए और कम से कम एक स्लाइड शामिल करना चाहिए। |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) जिसे [Section](../../section/) Zoom फ़्रेम के भीतर प्रदर्शित किया जाएगा। |

### रिटर्न मान

नए बनाए गए [ISectionZoomFrame](../../isectionzoomframe/)।

## टिप्पणी

यह उदाहरण एक [Section](../../section/) Zoom ऑब्जेक्ट को संग्रह के अंत में जोड़ने को दर्शाता है (मान लें कि \"Presentation.pptx\" प्रस्तुति में कम से कम दो सेक्शन हैं): 
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
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)