---
title: VerifySignature()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica la firma sui dati.
type: docs
weight: 27
url: /it/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metodo

Verifica la firma sui dati.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) firmata con **rgbSignature**. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Firma da verificare per i dati. |

### Valore di ritorno

True se il controllo della firma ha esito positivo, false altrimenti.

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) metodo

Verifica la firma sui dati. Non implementato.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Algoritmo da utilizzare per il hashing. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Firma da verificare per i dati. |

### Valore di ritorno

True se il controllo della firma ha esito positivo, false altrimenti.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [AsymmetricSignatureDeformatter](../)
* classe [HashAlgorithm](../../hashalgorithm/)
* spazio dei nomi [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)