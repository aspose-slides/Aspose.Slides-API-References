---
title: GetCertHashString()
second_title: Справка по API Aspose.Slides для C++
description: Получает SHA1-хеш текущего объекта в виде шестнадцатеричной строки.
type: docs
weight: 92
url: /ru/system.security.cryptography.x509certificates/x509certificate/getcerthashstring/
---
## X509Certificate::GetCertHashString() const метод


Получает [SHA1](../../../system.security.cryptography/sha1/) хеш для текущего объекта в виде шестнадцатеричной строки.

```cpp
virtual String System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHashString() const
```


### Возвращаемое значение

Шестнадцатеричная строка.

## X509Certificate::GetCertHashString(const HashAlgorithmName\&) const метод


Получает [SHA1](../../../system.security.cryptography/sha1/) хеш для текущего объекта в виде шестнадцатеричной строки.

```cpp
virtual String System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHashString(const HashAlgorithmName &hash_algorithm) const
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| hash_algorithm | const [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)\& | Имя алгоритма хеширования. |

### Возвращаемое значение

Шестнадцатеричная строка.

## См. также

* Класс [String](../../../system/string/)
* Класс [X509Certificate](../)
* Структура [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)
* Пространство имён [System::Security::Cryptography::X509Certificates](../../)
* Библиотека [Aspose.Slides](../../../)