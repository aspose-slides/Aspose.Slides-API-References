---
title: CreateSignature()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt die Signatur für die angegebenen Daten.
type: docs
weight: 1
url: /de/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) Methode


Erstellt die Signatur für die angegebenen Daten.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) zum Berechnen des Hashwerts für. |

### Rückgabewert

Berechnete Signatur in Form eines Byte-Arrays.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) Methode


Erstellt die Signatur für den angegebenen Hashwert.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Hash-Algorithmus, der beim Erstellen der Signatur verwendet wird. |

### Rückgabewert

Berechnete Signatur in Form eines Byte-Arrays.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [AsymmetricSignatureFormatter](../)
* Klasse [HashAlgorithm](../../hashalgorithm/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)