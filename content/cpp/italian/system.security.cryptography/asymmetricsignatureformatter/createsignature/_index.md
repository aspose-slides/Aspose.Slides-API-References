---
title: CreateSignature()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea la firma per i dati specificati.
type: docs
weight: 1
url: /it/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) metodo


Crea la firma per i dati specificati.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) per calcolare l'hash di. |

### Valore di ritorno

Firma calcolata in forma di array di byte.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) metodo


Crea la firma per il valore hash specificato.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Algoritmo hash da utilizzare per creare la firma. |

### Valore di ritorno

Firma calcolata in forma di array di byte.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [AsymmetricSignatureFormatter](../)
* Classe [HashAlgorithm](../../hashalgorithm/)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)