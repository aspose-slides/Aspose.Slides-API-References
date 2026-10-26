---
title: X509KeyUsageExtension()
second_title: Справка по API Aspose.Slides для C++
description: Конструктор по умолчанию.
type: docs
weight: 1
url: /ru/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() конструктор

Конструктор по умолчанию.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Закодированные данные использований ключа. |
| critical | **bool** | Признак критичности. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | Использования ключа. |
| critical | **bool** | Признак критичности. |

## См. также

* Перечисление [X509KeyUsageFlags](../../x509keyusageflags/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [X509KeyUsageExtension](../)
* Класс [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Пространство имён [System::Security::Cryptography::X509Certificates](../../)
* Библиотека [Aspose.Slides](../../../)