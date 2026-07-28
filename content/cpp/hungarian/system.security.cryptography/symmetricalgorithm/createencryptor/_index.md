---
title: CreateEncryptor()
second_title: Aspose.Slides C++ API referencia
description: Titkosítót hoz létre az algoritmus objektumához kapcsolódó paraméterekkel.
type: docs
weight: 183
url: /hu/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() metódus

Létrehozza a titkosítót a algoritmus objektumához kapcsolódó paraméterekkel.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

### Visszatérési érték

Újonnan létrehozott titkosító objektum.

## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metódus

Létrehozza a titkosítót explicit paraméterekkel.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Használandó kulcs. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Használandó kezdeti érték. |

### Visszatérési érték

Újonnan létrehozott titkosító objektum.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ICryptoTransform](../../icryptotransform/)
* Osztály [SymmetricAlgorithm](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)