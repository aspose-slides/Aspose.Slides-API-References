---
title: EndRead()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: निर्दिष्ट असिंक्रोनस पढ़ने के ऑपरेशन के पूरा होने तक प्रतीक्षा करता है।
type: docs
weight: 430
url: /hi/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) मेथड

निर्दिष्ट असिंक्रोनस पढ़ने के ऑपरेशन के पूर्ण होने तक प्रतीक्षा करता है।

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो एक असिंक्रोनस पढ़ने के ऑपरेशन का प्रतिनिधित्व करता है |

### वापसी मान

**asyncResult** द्वारा प्रतिनिधित्व किए गए पढ़ने के ऑपरेशन के दौरान पढ़े गए बाइट्स की संख्या

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [SslStream](../)
* नामस्थान [System::Net::Security](../../)
* लाइब्रेरी [Aspose.Slides](../../../)