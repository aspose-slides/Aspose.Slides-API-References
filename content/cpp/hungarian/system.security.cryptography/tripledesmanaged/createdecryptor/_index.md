---
title: CreateDecryptor()
second_title: Aspose.Slides C++ API hivatkozás
description: Kifejezett paraméterekkel hoz létre visszafejtő objektumot.
type: docs
weight: 14
url: /hu/system.security.cryptography/tripledesmanaged/createdecryptor/
---
## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metódus

Létrehoz egy visszafejtő objektumot kifejezett paraméterekkel.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A titkosítási kulcs bájt tömb formájában. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kezdeti érték bájt tömb formájában. |

### Visszatérési érték

Újonnan létrehozott visszafejtő objektum.

## TripleDESManaged::CreateDecryptor() metódus

Létrehoz egy visszafejtő objektumot az algoritmus objektum által definiált paraméterekkel.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metódus

Létrehoz egy visszafejtő objektumot az algoritmus objektum által definiált paraméterekkel.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ICryptoTransform](../../icryptotransform/)
* Osztály [TripleDESManaged](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)