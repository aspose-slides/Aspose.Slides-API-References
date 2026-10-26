---
title: UriComponents
second_title: Aspose.Slides for C++ API संदर्भ
description: URI घटकों का प्रतिनिधित्व करता है।
type: docs
weight: 3251
url: /hi/system/uricomponents/
---
## UriComponents enum

URI घटकों का प्रतिनिधित्व करता है।

```cpp
enum class UriComponents
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Scheme | 1 | Scheme डेटा। |
| UserInfo | 2 | UserInfo डेटा। |
| Host | 4 | Host डेटा। |
| Port | 8 | Port डेटा। |
| SchemeAndServer | n/a | Scheme, Host और Port डेटा। |
| Path | 16 | LocalPath डेटा। |
| Query | 32 | Query डेटा। |
| PathAndQuery | n/a | LocalPath और Query डेटा। |
| HttpRequestUrl | n/a | Scheme, Host, Port, Query और LocalPath डेटा। |
| Fragment | 64 | Fragment डेटा। |
| AbsoluteUri | n/a | Scheme, Host, Port, Quer, LocalPath और Fragment डेटा। |
| StrongPort | 128 | Port डेटा; यदि पोर्ट डेटा [Uri](../uri/) में उपस्थित नहीं है और डिफ़ॉल्ट पोर्ट Scheme को असाइन किया गया है, तो डिफ़ॉल्ट पोर्ट लौटाया जाता है; यदि कोई डिफ़ॉल्ट पोर्ट नहीं है, तो -1 लौटाया जाता है। |
| HostAndPort | n/a | Host और Port डेटा; यदि पोर्ट डेटा [Uri](../uri/) में उपस्थित नहीं है और डिफ़ॉल्ट पोर्ट Scheme को असाइन किया गया है, तो डिफ़ॉल्ट पोर्ट लौटाया जाता है। यदि कोई डिफ़ॉल्ट पोर्ट नहीं है, तो -1 लौटाया जाता है। |
| StrongAuthority | n/a | UserInfo, Host और Port डेटा।यदि पोर्ट डेटा [Uri](../uri/) में नहीं है और डिफ़ॉल्ट पोर्ट Scheme को असाइन किया गया है, तो डिफ़ॉल्ट पोर्ट लौटाया जाता है।यदि कोई डिफ़ॉल्ट पोर्ट नहीं है, तो -1 लौटाया जाता है। |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | निर्दिष्ट करता है कि डिलिमिटर शामिल किया जाना चाहिए। |
| SerializationInfoString | n/a | पूरा [Uri](../uri/) संदर्भ जो [Uri](../uri/) Serializers के लिए आवश्यक है। संदर्भ में IPv6 स्कोप शामिल है। |

## देखें भी

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)