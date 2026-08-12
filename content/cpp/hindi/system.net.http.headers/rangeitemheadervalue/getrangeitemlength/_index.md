---
title: GetRangeItemLength()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट इंडेक्स से पास किए गए स्ट्रिंग को RangeItemHeaderValue क्लास के एक इंस्टेंस में बदलता है।
type: docs
weight: 92
url: /hi/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) विधि

निर्दिष्ट इंडेक्स से पास किया गया स्ट्रिंग को [RangeItemHeaderValue](../) क्लास के एक इंस्टेंस में बदलता है।

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [String](../../../system/string/) | पार्स करने के लिए एक स्ट्रिंग। |
| startIndex | **int32_t** | पार्स करने के लिए प्रारंभ स्थिति। |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | वह इंस्टेंस जहाँ पार्स किया गया ऑब्जेक्ट सौंपा जाएगा। |

### वापसी मान

पार्स किए गए उपस्ट्रिंग की लंबाई लौटाता है, अन्यथा 0।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [RangeItemHeaderValue](../)
* नेमस्पेस [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)