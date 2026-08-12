---
title: HttpRequestCacheLevel
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: यह enum HTTP के लिए कैश सेटिंग्स का वर्णन करता है।
type: docs
weight: 40
url: /hi/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enum

The enum describes cache settings for HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Values

| नाम | मान | विवरण |
| --- | --- | --- |
| Default | 0 | एक संसाधन के लिए अनुरोध को या तो संसाधन की कैश की गई प्रति का उपयोग करके या सर्वर को संसाधन के लिए अनुरोध भेजकर पूरा करता है। |
| BypassCache | 1 | सर्वर का उपयोग करके अनुरोध को पूरा करता है। |
| CacheOnly | 2 | सदैव क्लाइंट कैश का उपयोग करके संसाधन प्राप्त करता है। |
| CacheIfAvailable | 3 | यदि संसाधन उपलब्ध हो तो कैश से संसाधन के लिए अनुरोध को पूरा करता है, अन्यथा सर्वर को अनुरोध भेजता है। |
| Revalidate | 4 | यदि क्लाइंट टाइमस्टैम्प सर्वर पर संसाधन के टाइमस्टैम्प के समान हो तो स्थानीय प्रति का उपयोग करता है। अन्यथा, सर्वर से संसाधन डाउनलोड किया जाता है। |
| Reload | 5 | एक संसाधन हमेशा सर्वर से डाउनलोड किया जाता है। |
| NoCacheNoStore | 6 | कैश से संसाधनों का उपयोग करके कभी भी अनुरोध को पूरा नहीं करता और संसाधनों को कैश नहीं करता। |
| CacheOrNextCacheOnly | 7 | स्थानीय कंप्यूटर के कैश या LAN पर रिमोट कैश से किसी संसाधन के लिए अनुरोध को पूरा करता है। |
| Refresh | 8 | स्थानीय कैश के अलावा सर्वर या किसी अन्य कैश का उपयोग करके अनुरोध को पूरा करता है। |

## See Also

* Namespace [System::Net::Cache](../)
* Library [Aspose.Slides](../../)