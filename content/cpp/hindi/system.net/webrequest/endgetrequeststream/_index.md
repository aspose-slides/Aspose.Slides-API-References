---
title: EndGetRequestStream()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट असिंक्रोनस ऑपरेशन द्वारा स्ट्रीम प्राप्त करने के पूर्ण होने तक प्रतीक्षा करता है।
type: docs
weight: 313
url: /hi/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) विधि


जब तक निर्दिष्ट असिंक्रोनस ऑपरेशन स्ट्रीम प्राप्त करने के लिए पूर्ण नहीं हो जाता, तब तक प्रतीक्षा करता है।

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो स्ट्रीम प्राप्त करने के लिए एक असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करता है। |

### वापसी मान

संसाधन में डेटा लिखने के लिए स्ट्रीम।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [WebRequest](../)
* नामस्थान [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)