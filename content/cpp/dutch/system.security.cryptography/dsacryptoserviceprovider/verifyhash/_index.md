---
title: VerifyHash()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert de handtekening van de gegevens.
type: docs
weight: 222
url: /nl/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) methode

Controleert de handtekening van de gegevens.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash berekend voor ontvangen gegevens. |
| str | const [String](../../../system/string/)\& | Naam van de gebruikte hash-algoritme. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekening zoals ontvangen. |

### Retourwaarde

True als handtekening geldig is, false anders.

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [DSACryptoServiceProvider](../)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)