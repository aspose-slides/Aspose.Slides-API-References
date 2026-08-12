---
title: Clear()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह से सभी SummaryZoomSection वस्तुओं को हटाता है।
type: docs
weight: 105
url: /hi/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() मेथड

संग्रह से सभी [SummaryZoomSection](../../summaryzoomsection/) वस्तुओं को हटाता है।

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## टिप्पणियाँ

उदाहरण दिखाता है कि कैसे Summary Zoom [Section](../../section/) तत्व को इंडेक्स द्वारा प्राप्त किया जाता है:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## संबंधित देखें

* क्लास [SummaryZoomSectionCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)