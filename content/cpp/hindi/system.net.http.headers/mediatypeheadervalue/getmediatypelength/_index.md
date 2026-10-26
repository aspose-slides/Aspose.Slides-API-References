---
title: GetMediaTypeLength()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: दिए गए स्ट्रिंग को निर्दिष्ट इंडेक्स से MediaTypeHeaderValue क्लास की एक इंस्टेंस में परिवर्तित करता है।
type: docs
weight: 144
url: /hi/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) विधि

पास किए गए स्ट्रिंग को निर्दिष्ट इंडेक्स से [MediaTypeHeaderValue](../) क्लास की एक इंस्टेंस में बदलता है।

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [String](../../../system/string/) | पार्स करने के लिए एक स्ट्रिंग। |
| startIndex | **int32_t** | पार्सिंग के लिए एक शुरुआती स्थिति। |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | डेलीगेट जो [MediaTypeHeaderValue](../) क्लास की इंस्टेंस बनाने के लिए उपयोग किया जाता है। |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | एक इंस्टेंस जहाँ एक पार्स किया गया ऑब्जेक्ट असाइन किया जाएगा। |

## वापसी मान

पार्स किए गए सबस्ट्रिंग की लंबाई लौटाता है, अन्यथा 0।

## संबंधित देखें

* टाइपडिफ़ [HeaderFunc](../../headerfunc/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [MediaTypeHeaderValue](../)
* नेमस्पेस [System::Net::Http::Headers](../../)
* लाइब्रेरी [Aspose.Slides](../../../)