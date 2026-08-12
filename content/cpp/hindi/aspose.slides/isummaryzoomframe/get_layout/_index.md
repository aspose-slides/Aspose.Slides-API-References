---
title: get_Layout()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: फ़्रेम में Summary Zoom अनुभागों की लेआउट प्राप्त करता है। डिफ़ॉल्ट मान GridLayout है।
type: docs
weight: 1
url: /hi/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() विधि

फ़्रेम में Summary Zoom अनुभागों की लेआउट प्राप्त करता है। डिफ़ॉल्ट मान GridLayout है।

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## विचार

उदाहरण दर्शाता है कि कैसे इंडेक्स द्वारा Summary Zoom [Section](../../section/) तत्व प्राप्त किया जाता है:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## संबंधित देखें

* एन्युम [ZoomLayout](../../zoomlayout/)
* क्लास [ISummaryZoomFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)