---
title: EndGetHostAddresses()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट असिंक्रोनस ऑपरेशन के पूरा होने तक प्रतीक्षा करता है जो एक नया IPHostEntry-class इंस्टेंस बनाता है।
type: docs
weight: 144
url: /hi/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) विधि


निर्दिष्ट असिंक्रोनस ऑपरेशन के पूरा होने तक प्रतीक्षा करता है जो एक नया IPHostEntry-class इंस्टेंस बनाता है।

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो एक असिंक्रोनस ऑपरेशन को दर्शाता है। |

### वापसी मान

एक नया बना हुआ IPHostEntry-class इंस्टेंस।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IPAddress](../../ipaddress/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Dns](../)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)