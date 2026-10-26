---
title: EndGetRequestStream()
second_title: C++ API रेफ़रेंस के लिये Aspose.Slides
description: निर्दिष्ट असिंक्रोनस ऑपरेशन के स्ट्रीम प्राप्त करने के पूरा होने तक प्रतीक्षा करता है।
type: docs
weight: 157
url: /hi/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) विधि

निर्दिष्ट असिंक्रोनस ऑपरेशन के पूरा होने तक प्रतीक्षा करता है जो एक स्ट्रीम प्राप्त करता है।

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो स्ट्रीम प्राप्त करने की असिंक्रोनस ऑपरेशन को दर्शाता है। |

### वापसी मान

संसाधन में डेटा लिखने के लिए स्ट्रीम।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [FileWebRequest](../)
* नामस्थान [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)