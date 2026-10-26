---
title: BeginRead()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक असिंक्रोनस पढ़ने का कार्य शुरू करता है।
type: docs
weight: 417
url: /hi/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) विधि

एक असिंक्रोनस रीड ऑपरेशन को शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डेटा पढ़ने के लिए बाइट ऐरे। |
| offset | **int32_t** | निर्दिष्ट ऐरे में बाइट में ऑफसेट। |
| count | **int32_t** | पढ़ने के लिए बाइट्स की संख्या। |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | ऑपरेशन समाप्त होने पर कॉल किया जाने वाला कॉलबैक। |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा जो प्रत्येक असिंक्रोनस रीड ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग होता है। |

### रिटर्न वैल्यू

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो प्रारंभ किए गए असिंक्रोनस रीड ऑपरेशन को दर्शाता है।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Object](../../../system/object/)
* क्लास [SslStream](../)
* नेमस्पेस [System::Net::Security](../../)
* लाइब्रेरी [Aspose.Slides](../../../)