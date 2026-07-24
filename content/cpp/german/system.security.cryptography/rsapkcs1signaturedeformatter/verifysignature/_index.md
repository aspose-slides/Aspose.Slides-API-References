---
title: VerifySignature()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft die Signatur des Daten-Hashs.
type: docs
weight: 40
url: /de/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) Methode

Überprüft die Signatur des Daten-Hashs.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hash, der für die Daten berechnet wurde. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Signatur, die für die Daten empfangen wurde. |

### Rückgabewert

True, wenn die Signatur gültig ist, andernfalls false.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [RSAPKCS1SignatureDeformatter](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)