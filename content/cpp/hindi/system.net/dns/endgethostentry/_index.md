---
title: EndGetHostEntry()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट असिंक्रोनस ऑपरेशन के पूरा होने तक प्रतीक्षा करता है जो एक नया IPHostEntry-class इंस्टेंस बनाता है।
type: docs
weight: 118
url: /hi/system.net/dns/endgethostentry/
---
## Dns::EndGetHostEntry(System::SharedPtr\<IAsyncResult\>) मेथड

निर्दिष्ट असिंक्रोनस ऑपरेशन के पूरा होने तक प्रतीक्षा करता है जो एक नया IPHostEntry-class इंस्टेंस बनाता है।

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostEntry(System::SharedPtr<IAsyncResult> asyncResult)
```

### आर्ग्युमेंट्स

| पैरामिटर | प्रकार | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो एक असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करता है। |

### वापसी मान

एक नया निर्मित IPHostEntry-class इंस्टेंस।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IPHostEntry](../../iphostentry/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Dns](../)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)