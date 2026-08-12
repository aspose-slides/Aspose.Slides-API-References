---
title: EndGetResponse()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: संसाधन के लिए निर्दिष्ट असिंक्रोनस अनुरोध के पूर्ण होने तक प्रतीक्षा करता है।
type: docs
weight: 508
url: /hi/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) विधि

संसाधन के लिए निर्दिष्ट असिंक्रोनस अनुरोध के समाप्त होने तक प्रतीक्षा करता है।

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो संसाधन के लिए असिंक्रोनस अनुरोध का प्रतिनिधित्व करता है। |

## रिटर्न मान

वेब प्रतिक्रिया।

## देखें

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [WebResponse](../../webresponse/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [HttpWebRequest](../)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)