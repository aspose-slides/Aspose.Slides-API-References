---
title: CreateDecryptor()
second_title: Aspose.Slides C++ API Referencia
description: Létrehozza a dekódoló objektumot explicit paraméterekkel.
type: docs
weight: 14
url: /hu/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metódus

Létrehozza a dekódoló objektumot explicit paraméterekkel.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Titkosítási kulcs bájt tömb formájában. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kezdeti érték bájt tömb formájában. |

### Visszatérési érték

Újonnan létrehozott dekódoló objektum.

## RijndaelManaged::CreateDecryptor() metódus

Létrehozza a dekódoló objektumot az algoritmus objektum által meghatározott paraméterekkel.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metódus

Létrehozza a dekódoló objektumot az algoritmus objektum által meghatározott paraméterekkel.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ICryptoTransform](../../icryptotransform/)
* Osztály [RijndaelManaged](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)