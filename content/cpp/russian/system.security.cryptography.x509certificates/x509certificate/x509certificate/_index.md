---
title: X509Certificate()
second_title: Справка API Aspose.Slides для C++
description: 
type: docs
weight: 1
url: /ru/system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) constructor




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закодированный сертификат. |

## X509Certificate::X509Certificate(const String\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Файл, из которого загружается сертификат. |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | Сертификат, используемый для инициализации этого объекта. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закодированный сертификат. |
| password | const [String](../../../system/string/)\& | Пароль, используемый для доступа к данным сертификата. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закодированный сертификат. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Пароль, используемый для доступа к данным сертификата. |

## X509Certificate::X509Certificate(const String\&, const String\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Файл, из которого загружается сертификат. |
| password | const [String](../../../system/string/)\& | Пароль, используемый для доступа к данным сертификата. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Файл, из которого загружается сертификат. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Пароль, используемый для доступа к данным сертификата. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закодированный сертификат. |
| password | const [String](../../../system/string/)\& | Пароль, используемый для доступа к данным сертификата. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Флаги, указывающие, как хранить ключ. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закодированный сертификат. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Пароль, используемый для доступа к данным сертификата. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Флаги, указывающие, как хранить ключ. |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Файл, из которого загружается сертификат. |
| password | const [String](../../../system/string/)\& | Пароль, используемый для доступа к данным сертификата. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Флаги, указывающие, как хранить ключ. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Файл, из которого загружается сертификат. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Пароль, используемый для доступа к данным сертификата. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Флаги, указывающие, как хранить ключ. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закодированный сертификат (публичная часть). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Последовательность байтов, представляющая закрытый ключ. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Флаги, указывающие, как хранить ключ. |

## См. также

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)