---
title: idx_get()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य ISummaryZoomSection.
type: docs
weight: 1
url: /hi/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) विधि

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
```

## टिप्पणी

उदाहरण दर्शाता है कि कैसे इंडेक्स द्वारा Summary Zoom [Section](../../section/) तत्व प्राप्त किया जाता है:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISummaryZoomSection](../../isummaryzoomsection/)
* क्लास [ISummaryZoomSectionCollection](../)
* नामस्थली [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)