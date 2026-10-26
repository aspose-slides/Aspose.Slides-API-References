---
title: SignHash()
second_title: Aspose.Slides voor C++ API-referentie
description: Berekent de handtekening voor de opgegeven hashwaarde.
type: docs
weight: 144
url: /nl/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) methode


Berekent de handtekening voor de opgegeven hashwaarde.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hashwaarde. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash-algoritme. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Padding-modus. Retourneert [RSA](../) handtekening voor de opgegeven hash. |

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RSASignaturePadding](../../rsasignaturepadding/)
* Klasse [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)