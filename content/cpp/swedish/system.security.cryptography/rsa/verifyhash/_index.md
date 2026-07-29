---
title: VerifyHash()
second_title: Aspose.Slides för C++ API-referens
description: Verifierar att signaturen för den angivna hashen är giltig.
type: docs
weight: 170
url: /sv/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) metod

Verifierar att signaturen för den angivna hashen är giltig.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hashvärde för de signerade data. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Signaturdata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritm. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Paddningsläge. return true om signaturen är giltig, annars - false. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [RSASignaturePadding](../../rsasignaturepadding/)
* Klass [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namnrymd [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)