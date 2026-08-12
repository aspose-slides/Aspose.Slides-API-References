---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Summary Zoom Frame ऑब्जेक्ट के लिए ISummaryZoomSectionCollection प्राप्त करता है।
type: docs
weight: 14
url: /hi/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() विधि


Summary Zoom Frame ऑब्जेक्ट के लिए [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) प्राप्त करता है।

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## टिप्पणी


उदाहरण सूचकांक द्वारा Summary Zoom [Section](../../section/) तत्व प्राप्त करने को प्रदर्शित करता है: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* वर्ग [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* वर्ग [SummaryZoomFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)