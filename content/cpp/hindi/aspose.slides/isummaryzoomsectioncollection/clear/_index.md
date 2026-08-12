---
title: Clear()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह से सभी SummaryZoomSection ऑब्जेक्ट हटाता है।
type: docs
weight: 66
url: /hi/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() विधि

संग्रह से सभी [SummaryZoomSection](../../summaryzoomsection/) वस्तुओं को हटाता है।

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## टिप्पणियाँ

उदाहरण इंडेक्स द्वारा Summary Zoom [Section](../../section/) तत्व प्राप्त करना दर्शाता है:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## संबंधित देखें

* क्लास [ISummaryZoomSectionCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)