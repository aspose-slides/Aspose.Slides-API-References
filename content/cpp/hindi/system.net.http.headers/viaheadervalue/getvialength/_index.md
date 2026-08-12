---
title: GetViaLength()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट इंडेक्स से पास की गई स्ट्रिंग को ViaHeaderValue क्लास की एक इंस्टेंस में बदलता है।
type: docs
weight: 131
url: /hi/system.net.http.headers/viaheadervalue/getvialength/
---
## ViaHeaderValue::GetViaLength(String, int32_t, System::SharedPtr\<Object\>\&) विधि

निर्दिष्ट इंडेक्स से पास की गई स्ट्रिंग को [ViaHeaderValue](../) क्लास की एक इंस्टेंस में बदलता है।

```cpp
static int32_t System::Net::Http::Headers::ViaHeaderValue::GetViaLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [String](../../../system/string/) | पार्स करने के लिये एक स्ट्रिंग। |
| startIndex | **int32_t** | पार्स करने के लिये शुरुआती स्थिति। |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | एक इंस्टेंस जहाँ पार्स किया गया ऑब्जेक्ट असाइन किया जाएगा। |

### रिटर्न वैल्यू

पार्स की गई सबस्ट्रिंग की लंबाई लौटाता है, अन्यथा 0।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [Object](../../../system/object/)
* क्लास [ViaHeaderValue](../)
* नेमस्पेस [System::Net::Http::Headers](../../)
* लाइब्रेरी [Aspose.Slides](../../../)