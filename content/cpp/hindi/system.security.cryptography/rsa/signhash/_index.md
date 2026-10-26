---
title: SignHash()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्धारित हैश मान के लिए हस्ताक्षर की गणना करता है।
type: docs
weight: 144
url: /hi/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) मेथड


निर्दिष्ट हैश मान के लिए हस्ताक्षर की गणना करता है।

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | हैश मान। |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | हैश एल्गोरिथ्म। |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | पैडिंग मोड। निर्दिष्ट हैश के लिए [RSA](../) हस्ताक्षर लौटाता है। |

## संबंधित देखें

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)