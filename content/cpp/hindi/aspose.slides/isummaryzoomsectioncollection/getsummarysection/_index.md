---
title: GetSummarySection()
second_title: Aspose.Slides for C++ API संदर्भ
description: दिए गए सेक्शन के लिए Summary Zoom Section तत्व लौटाता है।
type: docs
weight: 27
url: /hi/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) मेथड


दिए गए सेक्शन के लिए Summary Zoom [Section](../../section/) तत्व लौटाता है।

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) खोजने के लिए [ISection](../../isection/) |

### रिटर्न वैल्यू

[ISummaryZoomSection](../../isummaryzoomsection/) या null यदि संग्रह में सेक्शन के लिए तत्व नहीं है।

## टिप्पणियाँ



उदाहरण इंडेक्स द्वारा Summary Zoom [Section](../../section/) तत्व प्राप्त करने का प्रदर्शन करता है: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISection](../../isection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)