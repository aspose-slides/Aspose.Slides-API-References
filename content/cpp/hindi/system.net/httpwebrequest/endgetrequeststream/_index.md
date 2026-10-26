---
title: EndGetRequestStream()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: निर्धारित असिंक्रोनस ऑपरेशन द्वारा स्ट्रीम प्राप्त करने के पूरा होने तक प्रतीक्षा करता है।
type: docs
weight: 482
url: /hi/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) मेथड

निर्दिष्ट असिंक्रोनस ऑपरेशन द्वारा स्ट्रीम प्राप्त करने के पूरा होने तक प्रतीक्षा करता है।

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो स्ट्रीम प्राप्त करने के लिए असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करता है। |

### रिटर्न वैल्यू

संसाधन में डेटा लिखने के लिए स्ट्रीम।

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [HttpWebRequest](../)
* नामस्थान [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)