---
title: VerifySignature()
second_title: Aspose.Slides pro C++ API Reference
description: Ověřuje podpis na datech.
type: docs
weight: 27
url: /cs/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda

Ověřuje podpis na datech.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) podepsáno pomocí **rgbSignature**. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Podpis, který má být ověřen pro data. |

### Návratová hodnota

True pokud kontrola podpisu uspěje, false jinak.

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) metoda

Ověřuje podpis na datech. Není implementováno.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Algoritmus použitý pro hashování. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Podpis, který má být ověřen pro data. |

### Návratová hodnota

True pokud kontrola podpisu uspěje, false jinak.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [AsymmetricSignatureDeformatter](../)
* Třída [HashAlgorithm](../../hashalgorithm/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)