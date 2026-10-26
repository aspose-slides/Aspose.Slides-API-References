---
title: GetRegionScans()
second_title: Aspose.Slides के लिए C++ API रेफरेंस
description: निर्दिष्ट मैट्रिक्स रूपांतरण लागू करने के बाद इस Region को लगभग करने वाले RectangleF संरचनाओं की एक सरणी लौटाता है।
type: docs
weight: 27
url: /hi/system.drawing/region/getregionscans/
---
## Region::GetRegionScans(const SharedPtr\<Drawing2D::Matrix\>\&) const विधि

निर्दिष्ट मैट्रिक्स रूपांतरण लागू किए जाने के बाद इस [Region](../) को लगभग करने वाले [RectangleF](../../rectanglef/) संरचनाओं की एक सरणी लौटाता है।

```cpp
ArrayPtr<RectangleF> System::Drawing::Region::GetRegionScans(const SharedPtr<Drawing2D::Matrix> &matrix) const
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | एक Matrix जो क्षेत्र पर लागू करने के लिए ज्यामितीय रूपांतरण का प्रतिनिधित्व करता है। |

## संदर्भ

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [RectangleF](../../rectanglef/)
* क्लास [Matrix](../../../system.drawing.drawing2d/matrix/)
* क्लास [Region](../)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)