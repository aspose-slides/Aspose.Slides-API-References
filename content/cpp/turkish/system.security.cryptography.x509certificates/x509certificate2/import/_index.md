---
title: Import()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sertifika dosyasından bilgileri içe aktarır.
type: docs
weight: 300
url: /tr/system.security.cryptography.x509certificates/x509certificate2/import/
---
## X509Certificate2::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) method

Belirtilen sertifika dosyasından bilgileri içe aktarır.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifika dosyasının adı. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Sertifika verilerine erişmek için gereken şifre. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&, const String\&, X509KeyStorageFlags) method

Belirtilen sertifika dosyasından bilgileri içe aktarır.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifika dosyasının adı. |
| password | const [String](../../../system/string/)\& | Sertifika verilerine erişmek için gereken şifre. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) method

Belirtilen sertifika verilerinden bilgileri içe aktarır.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | X.509 sertifika verisi. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Sertifika verilerine erişmek için gereken şifre. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) method

Belirtilen sertifika verilerinden bilgileri içe aktarır.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sertifika dosyasının adı. |
| password | const [String](../../../system/string/)\& | Sertifika verilerine erişmek için gereken şifre. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&) method

Belirtilen sertifika dosyasından bilgileri içe aktarır.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifika dosyasının adı. |

## X509Certificate2::Import(const ByteArrayPtr\&) method

Belirtilen sertifika verilerinden bilgileri içe aktarır.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sertifika dosyasının adı. |

## İlgili

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)