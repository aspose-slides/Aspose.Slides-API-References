---
title: InsertSummaryZoomFrame()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: नया Summary Zoom फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर shape collection में सम्मिलित करता है।
type: docs
weight: 170
url: /hi/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) विधि

एक नया Summary Zoom फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर shape collection में रखता है।

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | वह शून्य-आधारित इंडेक्स जहाँ Summary Zoom फ्रेम को सम्मिलित किया जाना है। |
| x | **float** | नए Summary Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Summary Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Summary Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Summary Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |

### रिटर्न वैल्यू

नया बनाया गया [ISummaryZoomFrame](../../isummaryzoomframe/)।

## टिप्पणियाँ

यह विधि एक Summary Zoom फ्रेम बनाती है जो प्रस्तुति में सभी सेक्शन के सारांश लिंक को एकत्रित करता है।

यह उदाहरण एक Summary Zoom ऑब्जेक्ट को संग्रह के निर्दिष्ट इंडेक्स पर बनाने और सम्मिलित करने को दर्शाता है (मान लेते हैं कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## संदर्भ

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISummaryZoomFrame](../../isummaryzoomframe/)
* क्लास [ShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)