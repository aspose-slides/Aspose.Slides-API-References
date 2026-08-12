---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया Summary Zoom फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर उसे shape collection में सम्मिलित करता है।
type: docs
weight: 157
url: /hi/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) मेथड

एक नया Summary Zoom फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape collection में इसे सम्मिलित करता है।

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | Summary Zoom फ्रेम को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| x | **float** | नए Summary Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Summary Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Summary Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Summary Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |

### रिटर्न वैल्यू

नया बनाया गया [ISummaryZoomFrame](../../isummaryzoomframe/)।

## टिप्पणियाँ

यह मेथड एक Summary Zoom फ़्रेम बनाता है जो प्रस्तुति के सभी सेक्शन के लिए सारांश लिंक को एकत्रित करता है।

यह उदाहरण एक Summary Zoom ऑब्जेक्ट को कलेक्शन के निर्दिष्ट इंडेक्स पर बनाना और सम्मिलित करना दर्शाता है (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISummaryZoomFrame](../../isummaryzoomframe/)
* क्लास [IShapeCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)