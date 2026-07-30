---
title: VerifySignature()
second_title: Aspose.Slides pro C++ API Reference
description: Ověřuje podpis hash dat.
type: docs
weight: 40
url: /cs/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda

Ověřuje podpis hash dat.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hash vypočítaný pro data. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Podpis přijatý pro data. |

### Návratová hodnota

True pokud je podpis platný, false v opačném případě.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [RSAPKCS1SignatureDeformatter](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)