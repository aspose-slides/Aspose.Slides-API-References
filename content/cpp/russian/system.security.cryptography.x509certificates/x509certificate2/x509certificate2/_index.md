---
title: X509Certificate2()
second_title: Aspose.Slides для C++ Справочник API
description: Создаёт пустой X509Certificate2.
type: docs
weight: 1
url: /ru/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() конструктор

Создаёт пустой [X509Certificate2](../).

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Файл, из которого загружать сертификат. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | Объект [X509Certificate](../../x509certificate/). |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закодированный сертификат. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закодированный сертификат. |
| password | const [String](../../../system/string/)\& | Пароль сертификата. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закодированный сертификат. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Пароль сертификата. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закодированный сертификат. |
| password | const [String](../../../system/string/)\& | Пароль сертификата. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Флаги, указывающие, как хранить ключ. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закодированный сертификат. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Пароль сертификата. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Флаги, указывающие, как хранить ключ. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Файл, из которого загружать сертификат. |
| password | const [String](../../../system/string/)\& | Пароль сертификата. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Файл, из которого загружать сертификат. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Пароль сертификата. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Файл, из которого загружать сертификат. |
| password | const [String](../../../system/string/)\& | Пароль сертификата. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Флаги, указывающие, как хранить ключ. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Файл, из которого загружать сертификат. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Пароль сертификата. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Флаги, указывающие, как хранить ключ. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закодированный сертификат (публичная часть). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закрытый ключ. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Флаги, указывающие, как хранить ключ. |

## См. также

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)