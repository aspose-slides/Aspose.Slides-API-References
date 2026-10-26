---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides C++ API रेफ़रेंस के लिए
description: Summary Zoom Frame ऑब्जेक्ट के लिए ISummaryZoomSectionCollection प्राप्त करता है।
type: docs
weight: 14
url: /hi/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() विधि

[ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) को Summary Zoom Frame ऑब्जेक्ट के लिए प्राप्त करता है।

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## टिप्पणी

उदाहरण दर्शाता है कि इंडेक्स द्वारा Summary Zoom [Section](../../section/) तत्व को प्राप्त किया जाता है:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## अन्य देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* वर्ग [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* वर्ग [ISummaryZoomFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)