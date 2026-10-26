---
title: CreateEncryptor()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un encryptor con i parametri associati all'oggetto algoritmo.
type: docs
weight: 183
url: /it/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() metodo

Crea un encryptor con i parametri associati all'oggetto algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

### Valore di ritorno

Nuovo oggetto encryptor creato.

## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metodo

Crea un encryptor con parametri espliciti.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Chiave da utilizzare. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Valore iniziale da utilizzare. |

### Valore di ritorno

Nuovo oggetto encryptor creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICryptoTransform](../../icryptotransform/)
* Classe [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)