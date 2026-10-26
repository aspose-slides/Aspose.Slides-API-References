---
title: GetCertHash()
second_title: Справочник API Aspose.Slides для C++
description: Получает хеш текущего объекта в виде массива байтов.
type: docs
weight: 79
url: /ru/system.security.cryptography.x509certificates/x509certificate/getcerthash/
---
## X509Certificate::GetCertHash() const метод


Получает хеш для текущего объекта в виде массива байтов.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHash() const
```


### Возвращаемое значение

Значение хеша.

## X509Certificate::GetCertHash(const HashAlgorithmName\&) const метод


Получает хеш для текущего объекта в виде массива байтов.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHash(const HashAlgorithmName &hash_algorithm) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hash_algorithm | const [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)\& | Имя алгоритма хеширования. |

### Возвращаемое значение

Значение хеша.

## См. также

* Тип [ByteArrayPtr](../../../system/bytearrayptr/)
* Класс [X509Certificate](../)
* Структура [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)
* Пространство имён [System::Security::Cryptography::X509Certificates](../../)
* Библиотека [Aspose.Slides](../../../)