---
title: GetBytes()
second_title: Справочник API Aspose.Slides для C++
description: Заполняет существующие элементы массива случайными байтами.
type: docs
weight: 14
url: /ru/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) метод

Заполняет существующие элементы массива случайными байтами.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов для заполнения. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) метод

Заполняет существующий срез массива случайными байтами.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, часть которого нужно заполнить. |
| offset | int | Индекс начала среза. |
| count | int | Размер среза. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) метод

Заполняет существующие элементы представления массива случайными байтами.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Представление массива байтов для заполнения. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) метод

Заполняет существующий срез представления массива случайными байтами.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Представление массива байтов, часть которого нужно заполнить. |
| offset | int | Индекс начала среза. |
| count | int | Размер среза. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) метод

Заполняет существующие элементы стекового массива случайными байтами.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Стековый массив байтов для заполнения. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) метод

Заполняет существующий срез стекового массива случайными байтами.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Стековый массив байтов, часть которого нужно заполнить. |
| offset | int | Индекс начала среза. |
| count | int | Размер среза. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [RandomNumberGenerator](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)