---
title: CreateSignature()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: Tworzy podpis dla określonych danych.
type: docs
weight: 1
url: /pl/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) metoda


Tworzy podpis dla określonych danych.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) do obliczenia skrótu. |

### Wartość zwracana

Obliczony podpis w postaci tablicy bajtów.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) metoda


Tworzy podpis dla określonej wartości skrótu.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Algorytm skrótu używany przy tworzeniu podpisu. |

### Wartość zwracana

Obliczony podpis w postaci tablicy bajtów.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [AsymmetricSignatureFormatter](../)
* Klasa [HashAlgorithm](../../hashalgorithm/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)