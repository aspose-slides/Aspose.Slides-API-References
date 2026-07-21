---
title: Create()
second_title: Aspose.Slides для C++ справочника API
description: Создает реализацию алгоритма DSA по умолчанию.
type: docs
weight: 105
url: /ru/system.security.cryptography/dsa/create/
---
## DSA::Create() метод

Создает реализацию алгоритма [DSA](../) по умолчанию.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### Возвращаемое значение

[DSA](../) объект алгоритма.

## DSA::Create(const String\&) метод

Создает реализацию алгоритма [DSA](../) по умолчанию.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Должно быть "System.Security.Cryptography.DSACryptoServiceProvider". |

### Возвращаемое значение

[DSA](../) объект алгоритма.

## DSA::Create(int32_t) метод

Создает реализацию алгоритма [DSA](../) по умолчанию с указанным размером ключа.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Размер ключа в битах. |

## DSA::Create(const DSAParameters\&) метод

Создает реализацию алгоритма [DSA](../) по умолчанию с указанными параметрами.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | Параметры для алгоритма [DSA](../). |

## См. также

* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [DSA](../)
* Класс [String](../../../system/string/)
* Структура [DSAParameters](../../dsaparameters/)
* Пространство имен [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)