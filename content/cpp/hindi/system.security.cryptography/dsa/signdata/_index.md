---
title: SignData()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट हैश एल्गोरिदम का उपयोग करके निर्दिष्ट डेटा एरे का हैश मान निकालता है, और परिणाम पर हस्ताक्षर करता है।
type: docs
weight: 79
url: /hi/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) विधि

निर्दिष्ट डेटा एरे का हैश मान निर्दिष्ट हैश एल्गोरिदम का उपयोग करके गणना करता है, और परिणाम पर हस्ताक्षर करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | इनपुट डेटा एरे। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिदम। वापस [DSA](../) हस्ताक्षर इनपुट डेटा के लिए। |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) विधि

निर्दिष्ट डेटा एरे का हैश मान निर्दिष्ट हैश एल्गोरिदम का उपयोग करके गणना करता है, और परिणाम पर हस्ताक्षर करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | इनपुट डेटा एरे। |
| offset | **int32_t** | **data** में ऑफ़सेट। |
| count | **int32_t** | इनपुट डेटा के रूप में उपयोग करने के लिए बाइट्स की संख्या। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिदम। वापस [DSA](../) हस्ताक्षर इनपुट डेटा के लिए। |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) विधि

निर्दिष्ट बायनरी स्ट्रीम का हैश मान निर्दिष्ट हैश एल्गोरिदम का उपयोग करके गणना करता है, और परिणाम पर हस्ताक्षर करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | बायनरी स्ट्रीम। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिदम। वापस [DSA](../) हस्ताक्षर इनपुट डेटा के लिए। |

## संबंधित देखें

* टाइपडिफ [ByteArrayPtr](../../../system/bytearrayptr/)
* टाइपडिफ [StreamPtr](../../../system/streamptr/)
* क्लास [DSA](../)
* स्ट्रक्ट [HashAlgorithmName](../../hashalgorithmname/)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)