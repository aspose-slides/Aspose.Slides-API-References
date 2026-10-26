---
title: VerifySignature()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट डेटा के लिए DSA हस्ताक्षर सत्यापित करें।
type: docs
weight: 118
url: /hi/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) विधि

[DSA](../../dsa/) हस्ताक्षर को निर्दिष्ट डेटा के लिए सत्यापित करें।

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) **rgb_signature** के साथ हस्ताक्षरित। |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) हस्ताक्षर। |

### रिटर्न मान

true - यदि **rgb_signature** [DSA](../../dsa/) हस्ताक्षर से मेल खाता है जो **rgb_hash** पर गणना किया गया है, अन्यथा - false.

## देखें

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* क्लास [DSACryptoServiceProvider](../)
* नामस्थान [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)