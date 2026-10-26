---
title: VerifyHash()
second_title: Aspose.Slides for C++ API संदर्भ
description: डेटा हस्ताक्षर की जाँच करता है।
type: docs
weight: 222
url: /hi/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) विधि

डेटा हस्ताक्षर की जाँच करता है।

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | प्राप्त डेटा के लिए गणना किया गया हैश। |
| str | const [String](../../../system/string/)\& | उपयोग किए गए हैश एल्गोरिदम का नाम। |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | प्राप्त हस्ताक्षर। |

### वापसी मान

यदि हस्ताक्षर वैध है तो सत्य, अन्यथा असत्य।

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) विधि

निर्दिष्ट हैश के हस्ताक्षर की वैधता की जांच करता है।

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | हस्ताक्षरित डेटा का हैश मान। |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | हस्ताक्षर डेटा। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिदम। |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | पैडिंग मोड। यदि हस्ताक्षर वैध है तो सत्य लौटाएँ, अन्यथा असत्य। |

## संबंधित देखें

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [RSACryptoServiceProvider](../)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)