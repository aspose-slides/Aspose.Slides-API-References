---
title: VerifyHash()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob die Signatur des angegebenen Hashwertes gültig ist.
type: docs
weight: 170
url: /de/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) Methode

Überprüft, ob die Signatur des angegebenen Hashwertes gültig ist.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hashwert der signierten Daten. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Signaturdaten. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-Algorithmus. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Padding-Modus. Gibt true zurück, wenn die Signatur gültig ist, sonst - false. |

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RSASignaturePadding](../../rsasignaturepadding/)
* Klasse [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namensraum [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)