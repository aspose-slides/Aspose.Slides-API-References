---
title: IndexOf()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: निर्दिष्ट SummaryZoomSection ऑब्जेक्ट का सूचकांक लौटाता है।
type: docs
weight: 53
url: /hi/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) विधि

निर्दिष्ट [SummaryZoomSection](../../summaryzoomsection/) ऑब्जेक्ट का सूचकांक लौटाता है।

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### तर्क

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) ऑब्जेक्ट को खोजने के लिए [ISummaryZoomSection](../../isummaryzoomsection/)। |

### रिटर्न वैल्यू

[SummaryZoomSection](../../summaryzoomsection/) ऑब्जेक्ट का सूचकांक या -1 यदि [SummaryZoomSection](../../summaryzoomsection/) ऑब्जेक्ट इस संग्रह से नहीं है।

## टिप्पणी

यह उदाहरण इंडेक्स द्वारा Summary Zoom [Section](../../section/) तत्व प्राप्त करने को दर्शाता है: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISummaryZoomSection](../../isummaryzoomsection/)
* क्लास [ISummaryZoomSectionCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)