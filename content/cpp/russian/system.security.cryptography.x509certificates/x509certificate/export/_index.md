---
title: Export()
second_title: Справочник API Aspose.Slides для C++
description: Экспортирует текущий объект в массив байтов, используя указанный формат. НЕ РЕАЛИЗОВАНО.
type: docs
weight: 287
url: /ru/system.security.cryptography.x509certificates/x509certificate/export/
---
## X509Certificate::Export(X509ContentType) const метод

Экспортирует текущий объект в массив байтов, используя указанный формат. НЕ РЕАЛИЗОВАНО.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | Указывает, как форматировать выходные данные. |

### Возвращаемое значение

Массив байтов, представляющий текущий объект.

## X509Certificate::Export(X509ContentType, const SecureStringPtr\&) const метод

Экспортирует текущий объект в массив байтов, используя указанный формат. НЕ РЕАЛИЗОВАНО.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const SecureStringPtr &password) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | Указывает, как форматировать выходные данные. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Пароль, необходимый для доступа к данным сертификата. |

### Возвращаемое значение

Массив байтов, представляющий текущий объект.

## X509Certificate::Export(X509ContentType, const String\&) const метод

Экспортирует текущий объект в массив байтов, используя указанный формат. НЕ РЕАЛИЗОВАНО.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const String &password) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | Указывает, как форматировать выходные данные. |
| password | const [String](../../../system/string/)\& | Пароль, необходимый для доступа к данным сертификата. |

### Возвращаемое значение

Массив байтов, представляющий текущий объект.

## См. также

* Перечисление [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Класс [X509Certificate](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)