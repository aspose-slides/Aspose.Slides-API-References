---
title: VerifyHash()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट हैश के हस्ताक्षर की वैधता की पुष्टि करता है।
type: docs
weight: 170
url: /hi/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) विधि

निर्दिष्ट हैश के हस्ताक्षर की वैधता की जाँच करता है।

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | हस्ताक्षरित डेटा का हैश मान। |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | हस्ताक्षर डेटा। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिदम। |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | पैडिंग मोड। यदि हस्ताक्षर वैध है तो true लौटाएँ, अन्यथा - false। |

## संबंधित देखें

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)