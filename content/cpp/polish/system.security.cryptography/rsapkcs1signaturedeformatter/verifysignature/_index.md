---
title: VerifySignature()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Weryfikuje podpis skrótu danych.
type: docs
weight: 40
url: /pl/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda


Weryfikuje podpis skrótu danych.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hash obliczony dla danych. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Podpis otrzymany dla danych. |

### Wartość zwracana

True jeśli podpis jest prawidłowy, false w przeciwnym razie.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [RSAPKCS1SignatureDeformatter](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)