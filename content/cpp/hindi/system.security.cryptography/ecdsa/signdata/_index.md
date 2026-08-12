---
title: SignData()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट हैश एल्गोरिदम का उपयोग करके निर्दिष्ट डेटा एरे का हैश मान गणना करता है, और परिणाम पर हस्ताक्षर करता है।
type: docs
weight: 79
url: /hi/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) विधि

डेटा एरे के हैश मान की गणना निर्दिष्ट हैश एल्गोरिदम से करती है और परिणाम पर हस्ताक्षर करती है।

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | इनपुट डेटा एरे। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिदम। इनपुट डेटा के लिए ECDSA हस्ताक्षर वापस करता है। |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) विधि

डेटा एरे के हैश मान की गणना निर्दिष्ट हैश एल्गोरिदम से करती है और परिणाम पर हस्ताक्षर करती है।

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | इनपुट डेटा एरे। |
| offset | **int32_t** | **data** में ऑफ़सेट। |
| count | **int32_t** | इनपुट डेटा के रूप में उपयोग किए जाने वाले बाइट्स की संख्या। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिदम। इनपुट डेटा के लिए ECDSA हस्ताक्षर वापस करता है। |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) विधि

बाइनरी स्ट्रीम के हैश मान की गणना निर्दिष्ट हैश एल्गोरिदम से करती है और परिणाम पर हस्ताक्षर करती है।

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | बाइनरी स्ट्रीम। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिदम। इनपुट डेटा के लिए ECDSA हस्ताक्षर वापस करता है। |

## देखें भी

* टाइपडीफ़ [ByteArrayPtr](../../../system/bytearrayptr/)
* टाइपडीफ़ [StreamPtr](../../../system/streamptr/)
* क्लास [ECDsa](../)
* स्ट्रक्ट [HashAlgorithmName](../../hashalgorithmname/)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)