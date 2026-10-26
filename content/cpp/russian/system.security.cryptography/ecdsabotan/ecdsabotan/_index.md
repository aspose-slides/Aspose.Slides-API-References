---
title: ECDsaBotan()
second_title: Справочник API Aspose.Slides для C++
description: Конструктор. Использует параметры по умолчанию.
type: docs
weight: 1
url: /ru/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() конструктор


Конструктор. Использует параметры по умолчанию.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) конструктор


Конструктор.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Параметры алгоритма. |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) конструктор


Конструктор.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Кривая, используемая для создания пары публичного/приватного ключа. |

## ECDsaBotan::ECDsaBotan(int32_t) конструктор


Конструктор.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| key_size | **int32_t** | Размер ключа в битах. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) конструктор


Конструктор.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Публичный ключ Botan. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) конструктор


Конструктор.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Приватный ключ Botan. |

## См. также

* Класс [ECDsaBotan](../)
* Структура [ECParameters](../../ecparameters/)
* Структура [ECCurve](../../eccurve/)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)