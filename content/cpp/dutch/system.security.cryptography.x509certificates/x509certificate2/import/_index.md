---
title: Import()
second_title: Aspose.Slides voor C++ API-referentie
description: Importeert informatie van het opgegeven certificaatbestand.
type: docs
weight: 300
url: /nl/system.security.cryptography.x509certificates/x509certificate2/import/
---
## X509Certificate2::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) methode

Importeert informatie van het opgegeven certificaatbestand.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | De bestandsnaam van het certificaat. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Het wachtwoord dat vereist is om toegang te krijgen tot de certificaatgegevens. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&, const String\&, X509KeyStorageFlags) methode

Importeert informatie van het opgegeven certificaatbestand.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | De bestandsnaam van het certificaat. |
| password | const [String](../../../system/string/)\& | Het wachtwoord dat vereist is om toegang te krijgen tot de certificaatgegevens. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) methode

Importeert informatie van de opgegeven certificaatgegevens.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | De X.509 certificaatgegevens. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Het wachtwoord dat vereist is om toegang te krijgen tot de certificaatgegevens. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) methode

Importeert informatie van de opgegeven certificaatgegevens.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | De bestandsnaam van het certificaat. |
| password | const [String](../../../system/string/)\& | Het wachtwoord dat vereist is om toegang te krijgen tot de certificaatgegevens. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&) methode

Importeert informatie van het opgegeven certificaatbestand.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | De bestandsnaam van het certificaat. |

## X509Certificate2::Import(const ByteArrayPtr\&) methode

Importeert informatie van de opgegeven certificaatgegevens.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | De bestandsnaam van het certificaat. |

## Zie ook

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Bibliotheek [Aspose.Slides](../../../)