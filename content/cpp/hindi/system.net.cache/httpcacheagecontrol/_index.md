---
title: HttpCacheAgeControl
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: CacheAgeControl का उपयोग कैश्ड आइटम की आयु और ताजगी के संबंध में प्राथमिकताओं को निर्दिष्ट करने के लिए किया जाता है।
type: docs
weight: 53
url: /hi/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum

CacheAgeControl का उपयोग कैश्ड आइटम की आयु और ताजगी के संबंध में प्राथमिकताओं को निर्दिष्ट करने के लिए किया जाता है।

```cpp
enum class HttpCacheAgeControl
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| None | 0 | केवल आंतरिक उपयोग के लिए। |
| MinFresh | 1 | यदि समाप्ति से पहले शेष समय इस मान द्वारा निर्दिष्ट समय के बराबर या उससे अधिक है, तो सामग्री को कैश से लिया जा सकता है। |
| MaxAge | 2 | जब तक सामग्री इस मान द्वारा निर्दिष्ट आयु से अधिक पुरानी नहीं हो जाती, तब तक इसे कैश से लिया जा सकता है। |
| MaxStale | 4 | सामग्री के समाप्त हो जाने के बाद, जब तक इस मान द्वारा निर्दिष्ट समय समाप्त नहीं हो जाता, तब तक इसे कैश से लिया जा सकता है। |
| MaxAgeAndMinFresh | 3 | MaxAge और MinFresh। |
| MaxAgeAndMaxStale | 6 | MaxAge और MaxStale। |

## संबंधित देखें

* नेमस्पेस [System::Net::Cache](../)
* लाइब्रेरी [Aspose.Slides](../../)