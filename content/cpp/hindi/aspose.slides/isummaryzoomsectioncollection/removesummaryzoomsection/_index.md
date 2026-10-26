---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: कलेक्शन से Summary Zoom Section ऑब्जेक्ट को हटाएँ।
type: docs
weight: 40
url: /hi/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) मेथड

कलेक्शन से Summary Zoom [Section](../../section/) ऑब्जेक्ट हटाएँ।

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | वह [Section](../../section/) जिसके लिए Summary Zoom [Section](../../section/) तत्व को [ISection](../../isection/) हटाया जाना है। |
## टिप्पणियाँ

उदाहरण दर्शाता है कि कैसे इंडेक्स द्वारा Summary Zoom [Section](../../section/) तत्व प्राप्त किया जाता है:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISection](../../isection/)
* क्लास [ISummaryZoomSectionCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)