---
title: Import()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Importuje informace z určeného souboru certifikátu.
type: docs
weight: 300
url: /cs/system.security.cryptography.x509certificates/x509certificate2/import/
---
## X509Certificate2::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) metoda

Importuje informace z určeného souboru certifikátu.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | The certificate file name. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | The password required to access the certificate data. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&, const String\&, X509KeyStorageFlags) metoda


Importuje informace z určeného souboru certifikátu.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | The certificate file name. |
| password | const [String](../../../system/string/)\& | The password required to access the certificate data. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) metoda


Importuje informace ze zadaných dat certifikátu.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | The X.509 certificate data. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | The password required to access the certificate data. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) metoda


Importuje informace ze zadaných dat certifikátu.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | The certificate file name. |
| password | const [String](../../../system/string/)\& | The password required to access the certificate data. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&) metoda


Importuje informace z určeného souboru certifikátu.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | The certificate file name. |

## X509Certificate2::Import(const ByteArrayPtr\&) metoda


Importuje informace ze zadaných dat certifikátu.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | The certificate file name. |

## Viz také

* Výčtový typ [X509KeyStorageFlags](../../x509keystorageflags/)
* Definice typu [SecureStringPtr](../../../system.security/securestringptr/)
* Definice typu [ByteArrayPtr](../../../system/bytearrayptr/)
* Třída [String](../../../system/string/)
* Třída [X509Certificate2](../)
* Jmenný prostor [System::Security::Cryptography::X509Certificates](../../)
* Knihovna [Aspose.Slides](../../../)