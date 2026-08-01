---
title: VerifySignature()
second_title: Aspose.Slides voor C++ API-referentie
description: Verifieer DSA-handtekening voor de opgegeven gegevens.
type: docs
weight: 118
url: /nl/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) methode

Verifieer [DSA](../../dsa/) handtekening voor de opgegeven gegevens.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) ondertekend met **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) handtekening. |

### Retourwaarde

true - indien **rgb_signature** overeenkomt met de [DSA](../../dsa/) handtekening die is berekend op **rgb_hash**, anders - false.

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)