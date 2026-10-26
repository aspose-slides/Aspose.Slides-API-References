---
title: VerifySignature()
second_title: Aspose.Slides voor C++ API-referentie
description: Verifieer DSA-handtekening voor de opgegeven gegevens.
type: docs
weight: 14
url: /nl/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) methode


Verifieer [DSA](../) handtekening voor de opgegeven gegevens.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) ondertekend met **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) handtekening. |

### Retourwaarde

true - als **rgb_signature** overeenkomt met de [DSA](../) handtekening die is berekend op **rgb_hash**, anders - false.

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [DSA](../)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)