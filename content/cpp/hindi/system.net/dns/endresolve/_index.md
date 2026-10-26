---
title: EndResolve()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब तक निर्दिष्ट असिंक्रोनस ऑपरेशन नया IPHostEntry-class इंस्टेंस बनाने को पूरा नहीं करता, तब तक प्रतीक्षा करता है।
type: docs
weight: 170
url: /hi/system.net/dns/endresolve/
---
## Dns::EndResolve(System::SharedPtr\<IAsyncResult\>) विधि

Waits until the specified asynchronous operation to create a new IPHostEntry-class instance completes.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndResolve(System::SharedPtr<IAsyncResult> asyncResult)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) वस्तु जो एक असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करती है। |

### रिटर्न वैल्यू

एक नया बनाया गया IPHostEntry-class इंस्टेंस।

## संदर्भ देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IPHostEntry](../../iphostentry/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Dns](../)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)