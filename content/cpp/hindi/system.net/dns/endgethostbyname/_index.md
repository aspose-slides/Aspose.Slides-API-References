---
title: EndGetHostByName()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट असिंक्रोनस ऑपरेशन के समाप्त होने तक प्रतीक्षा करता है, जिससे एक नया IPHostEntry-class इंस्टेंस बनता है।
type: docs
weight: 66
url: /hi/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName(System::SharedPtr\<IAsyncResult\>) मेथड

निर्दिष्ट असिंक्रोनस ऑपरेशन के समाप्त होने तक प्रतीक्षा करता है, जिससे एक नया IPHostEntry-class इंस्टेंस बनता है।

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो एक असिंक्रोनस ऑपरेशन को दर्शाता है। |

### रिटर्न वैल्यू

एक नया निर्मित IPHostEntry-class इंस्टेंस।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IPHostEntry](../../iphostentry/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Dns](../)
* नामस्थान [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)