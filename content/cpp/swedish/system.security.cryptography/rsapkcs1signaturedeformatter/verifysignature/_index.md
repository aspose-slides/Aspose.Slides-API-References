---
title: VerifySignature()
second_title: Aspose.Slides för C++ API-referens
description: Verifierar signaturen för datahashen.
type: docs
weight: 40
url: /sv/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod

Verifierar signaturen för datahashen.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hash beräknad för data. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Signatur mottagen för data. |

### Returvärde

Sant om signaturen är giltig, falskt annars.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [RSAPKCS1SignatureDeformatter](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)