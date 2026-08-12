---
title: AddSummaryZoomSection()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: नया Summary Zoom Section ऑब्जेक्ट बनाता है और इसे संग्रह में जोड़ता है
type: docs
weight: 14
url: /hi/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) मेथड

नए Summary Zoom [Section](../../section/) ऑब्जेक्ट को बनाता है और इसे संग्रह में जोड़ता है

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) एक नए Summary Zoom [Section](../../section/) तत्व [ISection](../../isection/) |

### रिटर्न वैल्यू

जोड़ा गया [ISummaryZoomFrame](../../isummaryzoomframe/) तत्व

## टिप्पणी

यदि इस सेक्शन के लिए संग्रह में कोई तत्व पहले से मौजूद है, तो मौजूदा तत्व वापस किया जाता है।

उदाहरण इंडेक्स द्वारा Summary Zoom [Section](../../section/) तत्व प्राप्त करने को प्रदर्शित करता है:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISummaryZoomSection](../../isummaryzoomsection/)
* क्लास [ISection](../../isection/)
* क्लास [ISummaryZoomSectionCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)