---
title: GetSummarySection()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: दिए गए सेक्शन के लिए Summary Zoom Section तत्व लौटाता है।
type: docs
weight: 92
url: /hi/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) विधि


दिए गए सेक्शन के लिए Summary Zoom [Section](../../section/) तत्व लौटाता है।

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) खोजने के लिए [ISection](../../isection/) |

### वापसी मान

[ISummaryZoomSection](../../isummaryzoomsection/) या null यदि संग्रह में उस सेक्शन के लिए तत्व नहीं है।

## टिप्पणी



उदाहरण इंडेक्स द्वारा Summary Zoom [Section](../../section/) तत्व प्राप्त करने को दर्शाता है: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISection](../../isection/)
* Class [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)