---
title: CreateEncryptor()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehozza a titkosító objektumot explicit paraméterekkel.
type: docs
weight: 1
url: /hu/system.security.cryptography/rc2managed/createencryptor/
---
## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metódus


Létrehozza a titkosító objektumot explicit paraméterekkel.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Titkosítási kulcs bájt tömb formájában. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kezdeti érték bájt tömb formájában. |

### Visszatérési érték

Újonnan létrehozott titkosító objektum.

## RC2Managed::CreateEncryptor() metódus


Létrehozza a titkosító objektumot az algoritmus objektum által meghatározott paraméterekkel.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metódus


Létrehozza a titkosító objektumot az algoritmus objektum által meghatározott paraméterekkel.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [RC2Managed](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)