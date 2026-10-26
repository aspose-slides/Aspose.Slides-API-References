---
title: IndexOf()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट SummaryZoomSection ऑब्जेक्ट का सूचकांक लौटाता है।
type: docs
weight: 66
url: /hi/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) मेथड


निर्दिष्ट [SummaryZoomSection](../../summaryzoomsection/) ऑब्जेक्ट का सूचकांक लौटाता है।

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) ऑब्जेक्ट खोजने के लिए [ISummaryZoomSection](../../isummaryzoomsection/). |

### वापसी मान

एक [SummaryZoomSection](../../summaryzoomsection/) ऑब्जेक्ट का सूचकांक या -1 यदि [SummaryZoomSection](../../summaryzoomsection/) ऑब्जेक्ट इस संग्रह से नहीं है।

## टिप्पणियाँ



उदाहरण सूचकांक द्वारा Summary Zoom [Section](../../section/) तत्व को प्राप्त करने का प्रदर्शन करता है: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISummaryZoomSection](../../isummaryzoomsection/)
* क्लास [SummaryZoomSectionCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)