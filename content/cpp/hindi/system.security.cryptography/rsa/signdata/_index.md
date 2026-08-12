---
title: SignData()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट डेटा एरे का हैश मान निर्दिष्ट हैश एल्गोरिद्म और पैडिंग का उपयोग करके गणना करता है, और परिणाम पर हस्ताक्षर करता है।
type: docs
weight: 131
url: /hi/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) विधि


निर्दिष्ट डेटा एरे का हैश मान निर्दिष्ट हैश एल्गोरिद्म और पैडिंग का उपयोग करके गणना करता है, और परिणाम पर साइन करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### आर्ग्यूमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | इनपुट डेटा एरे। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | पैडिंग मोड। इनपुट डेटा के लिए [RSA](../) हस्ताक्षर लौटाता है। |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) विधि


निर्दिष्ट डेटा एरे का हैश मान निर्दिष्ट हैश एल्गोरिद्म और पैडिंग का उपयोग करके गणना करता है, और परिणाम पर साइन करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### आर्ग्यूमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | इनपुट डेटा एरे। |
| offset | **int32_t** | **data** में ऑफसेट। |
| count | **int32_t** | इनपुट डेटा के रूप में उपयोग किए जाने वाले बाइट्स की संख्या। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | पैडिंग मोड। इनपुट डेटा के लिए [RSA](../) हस्ताक्षर लौटाता है। |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) विधि


निर्दिष्ट बाइनरी स्ट्रीम का हैश मान निर्दिष्ट हैश एल्गोरिद्म और पैडिंग का उपयोग करके गणना करता है, और परिणाम पर साइन करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### आर्ग्यूमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | बाइनरी स्ट्रीम। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | पैडिंग मोड। इनपुट डेटा के लिए [RSA](../) हस्ताक्षर लौटाता है। |

## संबंधित देखें

* टाइपडिफ़ [ByteArrayPtr](../../../system/bytearrayptr/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ़ [StreamPtr](../../../system/streamptr/)
* क्लास [RSASignaturePadding](../../rsasignaturepadding/)
* क्लास [RSA](../)
* स्ट्रक्ट [HashAlgorithmName](../../hashalgorithmname/)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)