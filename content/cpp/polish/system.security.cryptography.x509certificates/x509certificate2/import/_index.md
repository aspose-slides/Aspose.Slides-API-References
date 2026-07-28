---
title: Import()
second_title: Aspose.Slides dla C++ - referencja API
description: Importuje informacje z określonego pliku certyfikatu.
type: docs
weight: 300
url: /pl/system.security.cryptography.x509certificates/x509certificate2/import/
---
## X509Certificate2::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) metoda

Importuje informacje z określonego pliku certyfikatu.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nazwa pliku certyfikatu. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Hasło wymagane do uzyskania dostępu do danych certyfikatu. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&, const String\&, X509KeyStorageFlags) metoda

Importuje informacje z określonego pliku certyfikatu.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nazwa pliku certyfikatu. |
| password | const [String](../../../system/string/)\& | Hasło wymagane do uzyskania dostępu do danych certyfikatu. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) metoda

Importuje informacje z określonych danych certyfikatu.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dane certyfikatu X.509. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Hasło wymagane do uzyskania dostępu do danych certyfikatu. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) metoda

Importuje informacje z określonych danych certyfikatu.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Nazwa pliku certyfikatu. |
| password | const [String](../../../system/string/)\& | Hasło wymagane do uzyskania dostępu do danych certyfikatu. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&) metoda

Importuje informacje z określonego pliku certyfikatu.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nazwa pliku certyfikatu. |

## X509Certificate2::Import(const ByteArrayPtr\&) metoda

Importuje informacje z określonych danych certyfikatu.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Nazwa pliku certyfikatu. |

## Zobacz także

* Wyliczenie [X509KeyStorageFlags](../../x509keystorageflags/)
* Definicja typu [SecureStringPtr](../../../system.security/securestringptr/)
* Definicja typu [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [X509Certificate2](../)
* Przestrzeń nazw [System::Security::Cryptography::X509Certificates](../../)
* Biblioteka [Aspose.Slides](../../../)