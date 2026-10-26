---
title: Import()
second_title: Aspose.Slides для C++: справочник API
description: Импортирует информацию из указанного файла сертификата.
type: docs
weight: 300
url: /ru/system.security.cryptography.x509certificates/x509certificate2/import/
---
## X509Certificate2::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) method

Импортирует информацию из указанного файла сертификата.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Имя файла сертификата. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Пароль, необходимый для доступа к данным сертификата. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&, const String\&, X509KeyStorageFlags) method

Импортирует информацию из указанного файла сертификата.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Имя файла сертификата. |
| password | const [String](../../../system/string/)\& | Пароль, необходимый для доступа к данным сертификата. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) method

Импортирует информацию из указанных данных сертификата.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Данные сертификата X.509. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Пароль, необходимый для доступа к данным сертификата. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) method

Импортирует информацию из указанных данных сертификата.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Имя файла сертификата. |
| password | const [String](../../../system/string/)\& | Пароль, необходимый для доступа к данным сертификата. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&) method

Импортирует информацию из указанного файла сертификата.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Имя файла сертификата. |

## X509Certificate2::Import(const ByteArrayPtr\&) method

Импортирует информацию из указанных данных сертификата.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Имя файла сертификата. |

## См. также

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)