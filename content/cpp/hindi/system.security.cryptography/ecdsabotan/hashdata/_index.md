---
title: HashData()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट डेटा एरे का हैश मान निर्दिष्ट हैश एल्गोरिद्म का उपयोग करके गणना करता है।
type: docs
weight: 105
url: /hi/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) विधि

निर्दिष्ट हैश एल्गोरिद्म का उपयोग करके निर्दिष्ट डेटा एरे का हैश मान गणना करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) हैश करने के लिए। |
| offset | **int32_t** | ऑफ़सेट **data** में। |
| count | **int32_t** | हैश करने के लिए बाइट्स की संख्या। |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | हैश एल्गोरिद्म। |

### रिटर्न मान

हैश किया गया डेटा।

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) विधि

निर्दिष्ट हैश एल्गोरिद्म का उपयोग करके निर्दिष्ट बाइनरी स्ट्रीम का हैश मान गणना करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | हैश करने के लिए बाइनरी स्ट्रीम। |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | हैश एल्गोरिद्म। |

### रिटर्न मान

हैश किया गया डेटा।

## सम्बन्धित देखें

* टाइपडिफ [ByteArrayPtr](../../../system/bytearrayptr/)
* टाइपडिफ [StreamPtr](../../../system/streamptr/)
* क्लास [ECDsaBotan](../)
* स्ट्रक्ट [HashAlgorithmName](../../hashalgorithmname/)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)