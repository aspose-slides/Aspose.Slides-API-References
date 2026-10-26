---
title: WebExceptionStatus
second_title: Aspose.Slides for C++ API संदर्भ
description: WebException क्लास के स्थिति कोड को सूचीबद्ध करता है।
type: docs
weight: 651
url: /hi/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

WebException क्लास के स्थिति कोड को सूचीबद्ध करता है।

```cpp
enum class WebExceptionStatus
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Success | 0 | कोई त्रुटि नहीं हुई। |
| NameResolutionFailure | 1 | नाम समाधान सेवा होस्ट नाम को हल नहीं कर सकी। |
| ConnectFailure | 2 | रिमोट सेवा बिंदु को ट्रांसपोर्ट स्तर पर संपर्क नहीं किया जा सका। |
| ReceiveFailure | 3 | रिमोट सर्वर से पूर्ण प्रतिक्रिया प्राप्त नहीं हुई। |
| SendFailure | 4 | रिमोट सर्वर को पूर्ण अनुरोध नहीं भेजा जा सका। |
| PipelineFailure | 5 | अनुरोध एक पाइपलाइन्ड अनुरोध था और प्रतिक्रिया प्राप्त होने से पहले कनेक्शन बंद हो गया। |
| RequestCanceled | 6 | अनुरोध रद्द किया गया या एक अवर्गीकृत त्रुटि हुई। |
| ProtocolError | 7 | सर्वर से प्राप्त प्रतिक्रिया पूर्ण थी लेकिन प्रोटोकॉल-स्तरीय त्रुटि इंगित करती है। |
| ConnectionClosed | 8 | कनेक्शन समय से पहले बंद हो गया। |
| TrustFailure | 9 | सर्वर प्रमाणपत्र को मान्य नहीं किया जा सका। |
| SecureChannelFailure | 10 | SSL का उपयोग करके कनेक्शन स्थापित करने के दौरान त्रुटि हुई। |
| ServerProtocolViolation | 11 | सर्वर प्रतिक्रिया वैध HTTP प्रतिक्रिया नहीं थी। |
| KeepAliveFailure | 12 | 'Keep-Alive' हेडर निर्दिष्ट करने वाले अनुरोध के लिए कनेक्शन अचानक बंद हो गया। |
| Pending | 13 | एक आंतरिक असिंक्रोनस अनुरोध लंबित है। |
| Timeout | 14 | एक अनुरोध के टाइम-आउट अवधि के दौरान कोई प्रतिक्रिया प्राप्त नहीं हुई। |
| ProxyNameResolutionFailure | 15 | नाम समाधान सेवा प्रॉक्सी होस्ट नाम को हल नहीं कर सकी। |
| UnknownError | 16 | अज्ञात प्रकार का अपवाद उत्पन्न हुआ है। |
| MessageLengthLimitExceeded | 17 | निर्दिष्ट सीमा से अधिक संदेश प्राप्त हुआ। |
| CacheEntryNotFound | 18 | निर्दिष्ट कैश एंट्री नहीं मिली। |
| RequestProhibitedByCachePolicy | 19 | अनुरोध को कैश नीति द्वारा अनुमति नहीं थी। |
| RequestProhibitedByProxy | 20 | यह अनुरोध प्रॉक्सी द्वारा अनुमति नहीं था। |

## संबंधित देखें

* नामस्थान [System::Net](../)
* लाइब्रेरी [Aspose.Slides](../../)