---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया Summary Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।
type: docs
weight: 157
url: /hi/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) method


एक नया Summary Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | नई Summary Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नई Summary Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नई Summary Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नई Summary Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |

### Return Value

नव निर्मित [ISummaryZoomFrame](../../isummaryzoomframe/)।

## Remarks

यह मेथड एक नया Summary Zoom बनाता है और इस प्रेजेंटेशन की सभी सेक्शन के लिए उसके अंदर ऑब्जेक्ट्स का संग्रह रखता है।

यह उदाहरण एक Summary Zoom ऑब्जेक्ट को संग्रह के अंत में जोड़ने को दर्शाता है (मान लें कि "Presentation.pptx" प्रेजेंटेशन में कम से कम दो सेक्शन हैं):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## See Also

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISummaryZoomFrame](../../isummaryzoomframe/)
* क्लास [ShapeCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)