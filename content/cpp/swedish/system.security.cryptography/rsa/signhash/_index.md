---
title: SignHash()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar signaturen för det angivna hashvärdet.
type: docs
weight: 144
url: /sv/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) metod

Beräknar signaturen för det angivna hashvärdet.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hashvärde. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hashalgoritm. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Paddingläge. returnerar [RSA](../) signatur för det angivna hashvärdet. |

## Se även

* Typdefinition [ByteArrayPtr](../../../system/bytearrayptr/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [RSASignaturePadding](../../rsasignaturepadding/)
* Klass [RSA](../)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)