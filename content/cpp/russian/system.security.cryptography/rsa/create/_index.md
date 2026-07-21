---
title: Create()
second_title: Aspose.Slides для C++ справочник API
description: Создает реализацию алгоритма RSA по умолчанию.
type: docs
weight: 183
url: /ru/system.security.cryptography/rsa/create/
---
## RSA::Create() метод

Создает реализацию алгоритма [RSA](../) по умолчанию.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) метод

Создает реализацию алгоритма [RSA](../) по умолчанию.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Должен быть "System.Security.Cryptography.RSACryptoServiceProvider". |

## RSA::Create(int32_t) метод

Создает реализацию алгоритма [RSA](../) по умолчанию с указанным размером ключа.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Размер ключа в битах. |

## RSA::Create(const RSAParameters\&) метод

Создает реализацию алгоритма [RSA](../) по умолчанию с указанными параметрами.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | Параметры для алгоритма [RSA](../). |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [RSA](../)
* Класс [String](../../../system/string/)
* Struct [RSAParameters](../../rsaparameters/)
* Пространство имён [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)