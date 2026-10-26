---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides for C++ API संदर्भ
description: संकलन से Summary Zoom Section ऑब्जेक्ट को हटाएँ।
type: docs
weight: 79
url: /hi/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) विधि

Remove Summary Zoom [Section](../../section/) ऑब्जेक्ट को संकलन से हटाएँ।

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) जिसके लिए Summary Zoom [Section](../../section/) तत्व को हटाया जाना है [ISection](../../isection/). |
## टिप्पणी



उदाहरण दिखाता है कि कैसे सूचकांक द्वारा Summary Zoom [Section](../../section/) तत्व प्राप्त किया जाए: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISection](../../isection/)
* क्लास [SummaryZoomSectionCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)