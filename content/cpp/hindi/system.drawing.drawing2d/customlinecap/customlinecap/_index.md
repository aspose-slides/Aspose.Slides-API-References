---
title: CustomLineCap()
second_title: Aspose.Slides for C++ API संदर्भ
description: CustomLineCap क्लास का नया उदाहरण बनाता है जो निर्दिष्ट गुणों के साथ उपयोगकर्ता-परिभाषित लाइन कैप का प्रतिनिधित्व करता है।
type: docs
weight: 1
url: /hi/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) निर्माता

[CustomLineCap](../) क्लास का नया उदाहरण बनाता है जो निर्दिष्ट गुणों के साथ उपयोगकर्ता-परिभाषित लाइन कैप का प्रतिनिधित्व करता है।

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | कस्टम कैप के लिए भराव निर्दिष्ट करता है |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | कस्टम कैप की रूपरेखा निर्दिष्ट करता है |
| baseCap | [LineCap](../../linecap/) | कस्टम कैप बनाने के लिए उपयोग की जाने वाली बेस लाइन कैप |
| baseInset | **float** | लाइन और कैप के बीच की दूरी निर्दिष्ट करता है |

## और देखें

* एन्यूम [LineCap](../../linecap/)
* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [GraphicsPath](../../graphicspath/)
* क्लास [CustomLineCap](../)
* नेमस्पेस [System::Drawing::Drawing2D](../../)
* लाइब्रेरी [Aspose.Slides](../../../)