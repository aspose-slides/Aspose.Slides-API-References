---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक नया Summary Zoom फ़्रेम बनाता है और उसे shape संग्रह के अंत में जोड़ता है।
type: docs
weight: 144
url: /hi/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) मेथड

एक नया Summary Zoom फ्रेम बनाता है और उसे shape संग्रह के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | नए Summary Zoom फ्रेम का x-निर्देशांक, पॉइंट में. |
| y | **float** | नए Summary Zoom फ्रेम का y-निर्देशांक, पॉइंट में. |
| width | **float** | नए Summary Zoom फ्रेम की चौड़ाई, पॉइंट में. |
| height | **float** | नए Summary Zoom फ्रेम की ऊँचाई, पॉइंट में. |

### रिटर्न मान

नया बनाया गया [ISummaryZoomFrame](../../isummaryzoomframe/)।

## टिप्पणियाँ

यह मेथड एक Summary Zoom फ्रेम बनाता है जो प्रस्तुति में सभी अनुभागों के सारांश लिंक्स को संग्रहीत करता है।

यह उदाहरण एक Summary Zoom ऑब्जेक्ट को संग्रह के अंत में जोड़ने को दर्शाता है (मान लें कि \"Presentation.pptx\" प्रस्तुति में कम से कम दो अनुभाग हैं): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## देखें भी

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISummaryZoomFrame](../../isummaryzoomframe/)
* क्लास [IShapeCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)