---
title: Import()
second_title: Aspose.Slides für C++ API-Referenz
description: Importiert Informationen aus der angegebenen Zertifikatdatei.
type: docs
weight: 300
url: /de/system.security.cryptography.x509certificates/x509certificate2/import/
---
## X509Certificate2::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) Methode

Importiert Informationen aus der angegebenen Zertifikatdatei.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Der Name der Zertifikatdatei. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Das Passwort, das zum Zugriff auf die Zertifikatsdaten erforderlich ist. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&, const String\&, X509KeyStorageFlags) Methode

Importiert Informationen aus der angegebenen Zertifikatdatei.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Der Name der Zertifikatdatei. |
| password | const [String](../../../system/string/)\& | Das Passwort, das zum Zugriff auf die Zertifikatsdaten erforderlich ist. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) Methode

Importiert Informationen aus den angegebenen Zertifikatsdaten.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Die X.509-Zertifikatsdaten. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Das Passwort, das zum Zugriff auf die Zertifikatsdaten erforderlich ist. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) Methode

Importiert Informationen aus den angegebenen Zertifikatsdaten.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Der Name der Zertifikatdatei. |
| password | const [String](../../../system/string/)\& | Das Passwort, das zum Zugriff auf die Zertifikatsdaten erforderlich ist. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&) Methode

Importiert Informationen aus der angegebenen Zertifikatdatei.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Der Name der Zertifikatdatei. |

## X509Certificate2::Import(const ByteArrayPtr\&) Methode

Importiert Informationen aus den angegebenen Zertifikatsdaten.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Der Name der Zertifikatdatei. |

## Siehe auch

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [X509Certificate2](../)
* Namensraum [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)