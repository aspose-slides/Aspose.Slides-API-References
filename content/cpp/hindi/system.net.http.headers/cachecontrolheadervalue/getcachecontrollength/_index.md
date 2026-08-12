---
title: GetCacheControlLength()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट सूचकांक से पास की गई स्ट्रिंग को CacheControlHeaderValue क्लास की एक उदाहरण में बदलता है।
type: docs
weight: 456
url: /hi/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) विधि

दिए गए स्ट्रिंग को निर्दिष्ट सूचकांक से [CacheControlHeaderValue](../) वर्ग की एक instance में बदलता है।

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### आर्ग्युमेंट

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | पार्स करने के लिए एक स्ट्रिंग। |
| startIndex | **int32_t** | पार्स करने के लिए आरंभिक स्थिति। |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | पार्स किए गए ऑब्जेक्ट में जोड़ी जाने वाली मान। |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | एक instance जहाँ पार्स किया गया ऑब्जेक्ट असाइन किया जाएगा। |

### वापसी मान

पार्स किए गए उपस्ट्रिंग की लंबाई, अन्यथा 0।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [CacheControlHeaderValue](../)
* नेमस्पेस [System::Net::Http::Headers](../../)
* लाइब्रेरी [Aspose.Slides](../../../)