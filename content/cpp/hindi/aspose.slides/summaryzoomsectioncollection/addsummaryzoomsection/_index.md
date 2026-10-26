---
title: AddSummaryZoomSection()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक नया Summary Zoom Section ऑब्जेक्ट बनाता है और उसे संग्रह में जोड़ता है
type: docs
weight: 53
url: /hi/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) विधि

नया Summary Zoom [Section](../../section/) ऑब्जेक्ट बनाता है और इसे संग्रह में जोड़ता है

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### पैरामीटर

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) एक नया Summary Zoom [Section](../../section/) तत्व [ISection](../../isection/) के लिए |

### वापसी मान

जोड़ा गया [ISummaryZoomFrame](../../isummaryzoomframe/) तत्व

## टिप्पणी

यदि इस अनुभाग के लिए कोई तत्व पहले से संग्रह में मौजूद है, तो मौजूदा तत्व वापस दिया जाता है।

उदाहरण दर्शाता है कि इंडेक्स द्वारा Summary Zoom [Section](../../section/) तत्व कैसे प्राप्त किया जाए: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## और देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISummaryZoomSection](../../isummaryzoomsection/)
* क्लास [ISection](../../isection/)
* क्लास [SummaryZoomSectionCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)