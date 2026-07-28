---
title: VerifySignature()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Weryfikuje podpis na danych.
type: docs
weight: 27
url: /pl/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda


Weryfikuje podpis na danych.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) signed with **rgbSignature**. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Signature to be verified for data. |

### Wartość zwracana

True if signature check succeeds, false otherwise.

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) metoda


Weryfikuje podpis na danych. Not implemented.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Algorithm to use for hashing. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Signature to be verified for data. |

### Wartość zwracana

True if signature check succeeds, false otherwise.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [AsymmetricSignatureDeformatter](../)
* Klasa [HashAlgorithm](../../hashalgorithm/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)