---
title: GetHeight()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट की लाइन स्पेसिंग, निर्दिष्ट Graphics ऑब्जेक्ट की वर्तमान इकाई में लौटाता है।
type: docs
weight: 14
url: /hi/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट की लाइन स्पेसिंग, निर्दिष्ट [Graphics](../../graphics/) ऑब्जेक्ट की वर्तमान इकाई में लौटाता है।

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | माप इकाइयों को निर्दिष्ट करने वाला [Graphics](../../graphics/) ऑब्जेक्ट |

## Font::GetHeight(float) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट की ऊँचाई, निर्दिष्ट लंबवत रिज़ॉल्यूशन वाले डिस्प्ले डिवाइस पर ड्रॉ की जाने पर लौटाता है।

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dpi | **float** | डिस्प्ले डिवाइस का लंबवत रिज़ॉल्यूशन |

### वापसी मान

फ़ॉन्ट की ऊँचाई पिक्सेल में

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Graphics](../../graphics/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)