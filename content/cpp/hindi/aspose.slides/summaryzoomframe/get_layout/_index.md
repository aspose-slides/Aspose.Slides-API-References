---
title: get_Layout()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: फ़्रेम में Summary Zoom सेक्शन का लेआउट प्राप्त करता है। डिफ़ॉल्ट मान GridLayout है।
type: docs
weight: 1
url: /hi/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() मेथड

फ़्रेम में Summary Zoom सेक्शन का लेआउट प्राप्त करता है। डिफ़ॉल्ट मान GridLayout है।

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## टिप्पणियाँ

उदाहरण दर्शाता है कि Index द्वारा Summary Zoom [Section](../../section/) तत्व को कैसे प्राप्त किया जाए:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## देखें

* Enum [ZoomLayout](../../zoomlayout/)
* क्लास [SummaryZoomFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)