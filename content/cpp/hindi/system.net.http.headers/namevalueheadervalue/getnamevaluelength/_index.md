---
title: GetNameValueLength()
second_title: Aspose.Slides for C++ API संदर्भ
description: परिभाषित इंडेक्स से पास की गई स्ट्रिंग को NameValueHeaderValue क्लास की एक इंस्टेंस में बदलता है।
type: docs
weight: 118
url: /hi/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) विधि

पारित किया गया स्ट्रिंग निर्दिष्ट इंडेक्स से [NameValueHeaderValue](../) क्लास की एक इंस्टेंस में परिवर्तित करता है।

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [String](../../../system/string/) | पार्स करने के लिए स्ट्रिंग। |
| startIndex | **int32_t** | पार्सिंग के लिए प्रारंभिक स्थिति। |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | वह इंस्टेंस जहाँ पार्स किया गया ऑब्जेक्ट असाइन किया जाएगा। |

### रिटर्न मान

पार्स किए गए सबस्ट्रिंग की लंबाई लौटाता है, अन्यथा 0।

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) विधि

पारित किया गया स्ट्रिंग निर्दिष्ट इंडेक्स से [NameValueHeaderValue](../) क्लास की एक इंस्टेंस में परिवर्तित करता है।

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [String](../../../system/string/) | पार्स करने के लिए स्ट्रिंग। |
| startIndex | **int32_t** | पार्सिंग के लिए प्रारंभिक स्थिति। |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | एक फ़ंक्शन जो [NameValueHeaderValue](../) क्लास की नई इंस्टेंस बनाने के लिए उपयोग किया जाता है। |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | वह इंस्टेंस जहाँ पार्स किया गया ऑब्जेक्ट असाइन किया जाएगा। |

### रिटर्न मान

पार्स किए गए सबस्ट्रिंग की लंबाई लौटाता है, अन्यथा 0।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* क्लास [String](../../../system/string/)
* क्लास [NameValueHeaderValue](../)
* नेमस्पेस [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)