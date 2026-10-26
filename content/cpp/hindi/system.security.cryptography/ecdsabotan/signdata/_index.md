---
title: SignData()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्धारित डेटा एरे का हैश मान गणना करता है और परिणाम पर हस्ताक्षर करता है।
type: docs
weight: 131
url: /hi/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) method

निर्दिष्ट डेटा एरे का हैश मान गणना करता है और परिणाम पर हस्ताक्षर करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | इनपुट डेटा एरे। इनपुट डेटा के लिए ECDSA सिग्नेचर लौटाता है। |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) method

निर्दिष्ट डेटा एरे का हैश मान गणना करता है और परिणाम पर हस्ताक्षर करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | इनपुट डेटा एरे। |
| offset | **int32_t** | डेटा में ऑफ़सेट। |
| count | **int32_t** | इनपुट डेटा के रूप में उपयोग करने के लिए बाइट्स की संख्या। इनपुट डेटा के लिए ECDSA सिग्नेचर लौटाता है। |

## ECDsaBotan::SignData(const StreamPtr\&) method

निर्दिष्ट बाइनरी स्ट्रीम का हैश मान गणना करता है और परिणाम पर हस्ताक्षर करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | बाइनरी स्ट्रीम। इनपुट डेटा के लिए ECDSA सिग्नेचर लौटाता है। |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method

निर्दिष्ट डेटा एरे का हैश मान निर्दिष्ट हैश एल्गोरिद्म का उपयोग करके गणना करता है और परिणाम पर हस्ताक्षर करता है।

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | इनपुट डेटा एरे। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। इनपुट डेटा के लिए ECDSA सिग्नेचर लौटाता है। |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method

निर्दिष्ट डेटा एरे का हैश मान निर्दिष्ट हैश एल्गोरिद्म का उपयोग करके गणना करता है और परिणाम पर हस्ताक्षर करता है।

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | इनपुट डेटा एरे। |
| offset | **int32_t** | डेटा में ऑफ़सेट। |
| count | **int32_t** | इनपुट डेटा के रूप में उपयोग करने के लिए बाइट्स की संख्या। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। इनपुट डेटा के लिए ECDSA सिग्नेचर लौटाता है। |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) method

निर्दिष्ट बाइनरी स्ट्रीम का हैश मान निर्दिष्ट हैश एल्गोरिद्म का उपयोग करके गणना करता है और परिणाम पर हस्ताक्षर करता है।

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | बाइनरी स्ट्रीम। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। इनपुट डेटा के लिए ECDSA सिग्नेचर लौटाता है। |

## संबंधित देखें

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)