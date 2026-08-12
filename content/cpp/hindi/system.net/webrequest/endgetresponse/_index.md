---
title: EndGetResponse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट असिंक्रोनस अनुरोध के संसाधन के पूर्ण होने तक प्रतीक्षा करता है।
type: docs
weight: 287
url: /hi/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) method

निर्दिष्ट असिंक्रोनस अनुरोध के संसाधन हेतु पूर्ण होने तक प्रतीक्षा करता है।

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो संसाधन के लिए एक असिंक्रोनस अनुरोध का प्रतिनिधित्व करता है। |

### वापसी मान

वेब प्रतिक्रिया।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [WebResponse](../../webresponse/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [WebRequest](../)
* नामस्थान [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)