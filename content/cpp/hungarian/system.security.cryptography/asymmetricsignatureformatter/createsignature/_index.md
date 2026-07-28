---
title: CreateSignature()
second_title: Aspose.Slides C++-hoz API referencia
description: Létrehozza az aláírást a megadott adatokhoz.
type: docs
weight: 1
url: /hu/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) metódus


Létrehozza az aláírást a megadott adatokhoz.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) a hash kiszámításához. |

### Visszatérési érték

Kiszámított aláírás bájt tömb formájában.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) metódus


Létrehozza az aláírást a megadott hash értékhez.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Hash algoritmus az aláírás létrehozásához. |

### Visszatérési érték

Kiszámított aláírás bájt tömb formájában.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [AsymmetricSignatureFormatter](../)
* Osztály [HashAlgorithm](../../hashalgorithm/)
* Névtér [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)