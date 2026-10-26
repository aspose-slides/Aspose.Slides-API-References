---
title: CreateDecryptor()
second_title: Aspose.Slides for C++ API Referenciája
description: Létrehozza a dekóder objektumot a megadott paraméterekkel.
type: docs
weight: 14
url: /hu/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metódus

Létrehozza a dekóder objektumot a megadott paraméterekkel.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Titkosítási kulcs bájt tömb formájában. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kezdeti érték bájt tömb formájában. |

### Visszatérési érték

Újonnan létrehozott dekóder objektum.

## RC2Managed::CreateDecryptor() metódus

Létrehozza a dekóder objektumot az algoritmus objektummal definiált paraméterekkel.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metódus

Létrehozza a dekóder objektumot az algoritmus objektummal definiált paraméterekkel.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ICryptoTransform](../../icryptotransform/)
* Osztály [RC2Managed](../)
* Névtér [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)