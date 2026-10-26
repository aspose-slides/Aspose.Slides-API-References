---
title: GetEntityTagLength()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट अनुक्रमांक से पास की गई स्ट्रिंग को EntityTagHeaderValue क्लास की एक इंस्टेंस में परिवर्तित करता है।
type: docs
weight: 118
url: /hi/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) मेथड


एक पास की गई स्ट्रिंग को निर्दिष्ट इंडेक्स से [EntityTagHeaderValue](../) क्लास की एक इंस्टेंस में परिवर्तित करता है।

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [String](../../../system/string/) | पार्स करने के लिए एक स्ट्रिंग। |
| startIndex | **int32_t** | पार्सिंग के लिए एक प्रारंभिक स्थिति। |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | एक इंस्टेंस जहाँ पार्स किया गया ऑब्जेक्ट असाइन किया जाएगा। |

### रिटर्न वैल्यू

पार्स की गई सबस्ट्रिंग की लंबाई, अन्यथा 0।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [EntityTagHeaderValue](../)
* नेमस्पेस [System::Net::Http::Headers](../../)
* लाइब्रेरी [Aspose.Slides](../../../)