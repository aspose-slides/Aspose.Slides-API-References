---
title: CreateSignature()
second_title: Aspose.Slides för C++ API-referens
description: Skapar signaturen för den angivna datan.
type: docs
weight: 1
url: /sv/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) metod

Skapar signaturen för den angivna datan.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) för att beräkna hash för. |

### Returvärde

Beräknad signatur i bytearray-form.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) metod

Skapar signaturen för det angivna hash-värdet.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Hash-algoritm som ska användas när signaturen skapas. |

### Returvärde

Beräknad signatur i bytearray-form.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [AsymmetricSignatureFormatter](../)
* Klass [HashAlgorithm](../../hashalgorithm/)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)