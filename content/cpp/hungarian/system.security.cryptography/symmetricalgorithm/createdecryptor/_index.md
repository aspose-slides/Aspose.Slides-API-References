---
title: CreateDecryptor()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza a visszafejtőt az algoritmus objektumhoz kapcsolódó paraméterekkel.
type: docs
weight: 196
url: /hu/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() metódus


Létrehozza a visszafejtőt a algoritmus objektumhoz kapcsolódó paraméterekkel.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```


### Visszatérési érték

Újonnan létrehozott visszafejtő objektum.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metódus


Létrehozza a visszafejtőt kifejezett paraméterekkel.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Használandó kulcs. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Használandó kezdeti érték. |

### Visszatérési érték

Újonnan létrehozott visszafejtő objektum.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ICryptoTransform](../../icryptotransform/)
* Osztály [SymmetricAlgorithm](../)
* Névterület [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)