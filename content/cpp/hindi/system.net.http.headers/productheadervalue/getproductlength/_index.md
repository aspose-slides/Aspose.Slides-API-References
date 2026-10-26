---
title: GetProductLength()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: दिए गए स्ट्रिंग को निर्दिष्ट अनुक्रमांक से ProductHeaderValue क्लास की एक इंस्टेंस में परिवर्तित करता है।
type: docs
weight: 105
url: /hi/system.net.http.headers/productheadervalue/getproductlength/
---
## ProductHeaderValue::GetProductLength(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) मेथड

दिए गए स्ट्रिंग को निर्दिष्ट अनुक्रमांक से [ProductHeaderValue](../) क्लास की एक इंस्टेंस में परिवर्तित करता है।

```cpp
static int32_t System::Net::Http::Headers::ProductHeaderValue::GetProductLength(String input, int32_t startIndex, System::SharedPtr<ProductHeaderValue> &parsedValue)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | [String](../../../system/string/) | पार्स करने के लिए एक स्ट्रिंग। |
| startIndex | **int32_t** | पार्स करने के लिए एक प्रारंभिक स्थिति। |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | एक इंस्टेंस जहाँ पार्स किया गया ऑब्जेक्ट सौंपा जाएगा। |

### रिटर्न वैल्यू

पार्स किए गए सबस्ट्रिंग की लंबाई लौटाता है, अन्यथा 0।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [ProductHeaderValue](../)
* नेमस्पेस [System::Net::Http::Headers](../../)
* लाइब्रेरी [Aspose.Slides](../../../)