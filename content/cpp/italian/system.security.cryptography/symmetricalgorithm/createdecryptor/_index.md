---
title: CreateDecryptor()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un decrittatore con i parametri associati all'oggetto algoritmo.
type: docs
weight: 196
url: /it/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() metodo


Crea un decrittatore con i parametri associati all'oggetto algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```


### Valore di ritorno

Oggetto decrittatore appena creato.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metodo


Crea un decrittatore con parametri espliciti.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Chiave da usare. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Valore iniziale da usare. |

### Valore di ritorno

Oggetto decrittatore appena creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICryptoTransform](../../icryptotransform/)
* Classe [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)