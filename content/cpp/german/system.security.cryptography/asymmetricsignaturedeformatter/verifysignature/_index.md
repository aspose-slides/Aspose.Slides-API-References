---
title: VerifySignature()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft die Signatur der Daten.
type: docs
weight: 27
url: /de/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) Methode


Überprüft die Signatur der Daten.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) signiert mit **rgbSignature**. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Signatur, die für die Daten zu verifizieren ist. |

### Rückgabewert

True, wenn die Signaturprüfung erfolgreich ist, sonst false.

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) Methode


Überprüft die Signatur der Daten. Nicht implementiert.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Algorithmus, der zum Hashen verwendet wird. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Signatur, die für die Daten zu verifizieren ist. |

### Rückgabewert

True, wenn die Signaturprüfung erfolgreich ist, sonst false.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [AsymmetricSignatureDeformatter](../)
* Klasse [HashAlgorithm](../../hashalgorithm/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)