---
title: CreateSignature()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří podpis pro zadaná data.
type: docs
weight: 1
url: /cs/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) metoda


Vytvoří podpis pro zadaná data.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) pro výpočet hash. |

### Návratová hodnota

Vypočtený podpis ve formě pole bytů.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) metoda


Vytvoří podpis pro zadanou hodnotu hash.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Hash algoritmus použitý při vytváření podpisu. |

### Návratová hodnota

Vypočtený podpis ve formě pole bytů.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [AsymmetricSignatureFormatter](../)
* Třída [HashAlgorithm](../../hashalgorithm/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)