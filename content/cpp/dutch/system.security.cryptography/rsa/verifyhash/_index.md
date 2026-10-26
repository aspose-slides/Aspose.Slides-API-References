---
title: VerifyHash()
second_title: Aspose.Slides voor C++ API-referentie
description: Verifieert dat de handtekening van de opgegeven hash geldig is.
type: docs
weight: 170
url: /nl/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) methode

Verifieert dat de handtekening van de opgegeven hash geldig is.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hashwaarde van de ondertekende gegevens. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Handtekeninggegevens. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Padding-modus. retourneert true als de handtekening geldig is, anders - false. |

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RSASignaturePadding](../../rsasignaturepadding/)
* Klasse [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)