---
title: Equals()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: निर्धारित करता है कि क्या निर्दिष्ट क्षेत्र वर्तमान वस्तु द्वारा दर्शाए गए क्षेत्र के समान है निर्दिष्ट ड्रॉइंग सतह पर।
type: docs
weight: 157
url: /hi/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) विधि

निर्धारित करता है कि क्या निर्दिष्ट क्षेत्र वर्तमान वस्तु द्वारा दर्शाए गए क्षेत्र के समान है निर्दिष्ट ड्रॉइंग सतह पर।

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | इस क्षेत्र की तुलना के लिए यह क्षेत्र |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | एक ड्रॉइंग सतह |

### वापसी मान

True if the interior of the specified region is identical to the interior of the region represented by the current objcet when the transformation associated with the **g** parameter is applied; otherwise - false

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Region](../)
* क्लास [Graphics](../../graphics/)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)