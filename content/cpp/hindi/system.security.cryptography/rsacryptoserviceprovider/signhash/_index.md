---
title: SignHash()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट हैश मान के लिए हस्ताक्षर की गणना करता है।
type: docs
weight: 196
url: /hi/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) मेथड

निर्दिष्ट हैश मान के लिए हस्ताक्षर की गणना करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | हैश मान। |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | हैश एल्गोरिद्म। |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | पैडिंग मोड। [RSA](../../rsa/) हस्ताक्षर निर्दिष्ट हैश के लिए लौटाता है। |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) मेथड

निर्दिष्ट इनपुट मान का हस्ताक्षर गणना करता है। लागू नहीं है।

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षरित करने के लिए डेटा का हैश मान। |
| str | const [String](../../../system/string/)\& | हैश बनाने के लिए उपयोग किया गया हैश एल्गोरिद्म पहचानकर्ता। |

### वापसी मान

[RSA](../../rsa/) निर्दिष्ट डेटा के लिए हस्ताक्षर।

## संबंधित देखें

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [RSASignaturePadding](../../rsasignaturepadding/)
* क्लास [RSACryptoServiceProvider](../)
* क्लास [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* नेमस्पेस [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)