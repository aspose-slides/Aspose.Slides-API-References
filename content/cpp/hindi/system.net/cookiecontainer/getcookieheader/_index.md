---
title: GetCookieHeader()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट URI के साथ जुड़े कुकीज़ को शामिल करने वाला एक HTTP हेडर लौटाता है।
type: docs
weight: 170
url: /hi/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) विधि

निर्दिष्ट URI के साथ जुड़े कुकीज़ को शामिल करने वाला एक HTTP हेडर वापस करता है।

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | एक URI जिसके लिए हेडर नाम बनाया जाएगा। |

### रिटर्न वैल्यू

एक HTTP हेडर जिसमें निर्दिष्ट URI के साथ जुड़े कुकीज़ होते हैं।

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) विधि

निर्दिष्ट URI के साथ जुड़े कुकीज़ को शामिल करने वाला एक HTTP हेडर वापस करता है।

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | एक URI जिसके लिए हेडर नाम बनाया जाएगा। |
| optCookie2 | [String](../../../system/string/)\& | आउटपुट पैरामीटर जहाँ अधिकतम समर्थित संस्करण वाली कुकी असाइन की जाएगी। |

### रिटर्न वैल्यू

एक HTTP हेडर जिसमें निर्दिष्ट URI के साथ जुड़े कुकीज़ होते हैं।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [Uri](../../../system/uri/)
* क्लास [CookieContainer](../)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)