---
title: VerifyData()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट डेटा के हस्ताक्षर की वैधता की पुष्टि करता है।
type: docs
weight: 157
url: /hi/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) विधि

निर्दिष्ट डेटा के हस्ताक्षर की वैधता की पुष्टि करता है।

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षरित डेटा। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षर डेटा। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | पैडिंग मोड। यदि हस्ताक्षर वैध है तो true लौटाएँ, अन्यथा false। |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) विधि

निर्दिष्ट डेटा के हस्ताक्षर की वैधता की पुष्टि करता है।

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षरित डेटा। |
| offset | **int32_t** | **data** में ऑफ़सेट। |
| count | **int32_t** | हैश करने के लिए बाइट्स की संख्या। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षर डेटा। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | पैडिंग मोड। यदि हस्ताक्षर वैध है तो true लौटाएँ, अन्यथा false। |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) विधि

निर्दिष्ट बाइनरी स्ट्रीम के हस्ताक्षर की वैधता की पुष्टि करता है।

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | हस्ताक्षरित डेटा। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षर डेटा। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | पैडिंग मोड। यदि हस्ताक्षर वैध है तो true लौटाएँ, अन्यथा false। |

## संबंधित देखें

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* क्लास [RSASignaturePadding](../../rsasignaturepadding/)
* क्लास [RSA](../)
* स्ट्रक्ट [HashAlgorithmName](../../hashalgorithmname/)
* नेमस्पेस [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)