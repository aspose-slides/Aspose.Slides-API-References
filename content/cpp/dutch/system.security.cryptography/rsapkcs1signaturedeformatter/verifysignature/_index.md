---
title: VerifySignature()
second_title: Aspose.Slides voor C++ API-referentie
description: Verifieert de handtekening van de gegevenshash.
type: docs
weight: 40
url: /nl/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) methode

Verifieert de handtekening van de gegevenshash.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hash berekend voor de gegevens. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Handtekening ontvangen voor de gegevens. |

### Retourwaarde

True als de handtekening geldig is, false anders.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [RSAPKCS1SignatureDeformatter](../)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)