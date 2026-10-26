---
title: VerifyData()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: डेटा सिग्नेचर की जाँच करता है।
type: docs
weight: 209
url: /hi/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method

डेटा सिग्नेचर की जाँच करता है।

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) के लिये सिग्नेचर की जाँच करने हेतु। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | प्राप्त सिग्नेचर। |

### वापसी मान

यदि सिग्नेचर वैध है तो सही, अन्यथा गलत।

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

निर्दिष्ट डेटा के सिग्नेचर की वैधता की जाँच करता है।

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | साइन किया गया डेटा। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | सिग्नेचर डेटा। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। यदि सिग्नेचर वैध है तो सही, अन्यथा - गलत। |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method

निर्दिष्ट डेटा के सिग्नेचर की वैधता की जाँच करता है।

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | साइन किया गया डेटा। |
| offset | **int32_t** | **data** में ऑफसेट। |
| count | **int32_t** | हैश करने के लिए बाइट्स की संख्या। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | सिग्नेचर डेटा। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। यदि सिग्नेचर वैध है तो सही, अन्यथा - गलत। |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

निर्दिष्ट बाइनरी स्ट्रीम के सिग्नेचर की वैधता की जाँच करता है।

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | साइन किया गया डेटा। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | सिग्नेचर डेटा। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। यदि सिग्नेचर वैध है तो सही, अन्यथा - गलत। |

## देखें

* टाइपडिफ [ByteArrayPtr](../../../system/bytearrayptr/)
* टाइपडिफ [StreamPtr](../../../system/streamptr/)
* क्लास [DSACryptoServiceProvider](../)
* स्ट्रक्चर [HashAlgorithmName](../../hashalgorithmname/)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)