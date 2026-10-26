---
title: Import()
second_title: Aspose.Slides for C++ API Referenciája
description: Importálja az információkat a megadott tanúsítványfájlból.
type: docs
weight: 300
url: /hu/system.security.cryptography.x509certificates/x509certificate2/import/
---
## X509Certificate2::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) metódus

Importálja az információkat a megadott tanúsítványfájlból.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A tanúsítványfájl neve. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | A tanúsítványadatokhoz való hozzáféréshez szükséges jelszó. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&, const String\&, X509KeyStorageFlags) metódus

Importálja az információkat a megadott tanúsítványfájlból.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A tanúsítványfájl neve. |
| password | const [String](../../../system/string/)\& | A tanúsítványadatokhoz való hozzáféréshez szükséges jelszó. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) metódus

Importálja az információkat a megadott tanúsítványadatokból.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Az X.509 tanúsítványadat. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | A tanúsítványadatokhoz való hozzáféréshez szükséges jelszó. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) metódus

Importálja az információkat a megadott tanúsítványadatokból.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A tanúsítványfájl neve. |
| password | const [String](../../../system/string/)\& | A tanúsítványadatokhoz való hozzáféréshez szükséges jelszó. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&) metódus

Importálja az információkat a megadott tanúsítványfájlból.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A tanúsítványfájl neve. |

## X509Certificate2::Import(const ByteArrayPtr\&) metódus

Importálja az információkat a megadott tanúsítványadatokból.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A tanúsítványfájl neve. |

## Lásd még

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)