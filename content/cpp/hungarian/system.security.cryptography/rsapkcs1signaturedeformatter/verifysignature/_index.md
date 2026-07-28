---
title: VerifySignature()
second_title: Aspose.Slides C++ API Referenciája
description: Ellenőrzi az adat hash aláírását.
type: docs
weight: 40
url: /hu/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metódus

Ellenőrzi az adat hash aláírását.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A adat hash számítása. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az adat aláírása. |

### Visszatérési érték

Igaz, ha az aláírás érvényes, hamis egyébként.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [RSAPKCS1SignatureDeformatter](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)