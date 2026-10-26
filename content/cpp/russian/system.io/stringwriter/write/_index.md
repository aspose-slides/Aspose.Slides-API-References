---
title: Write()
second_title: Справочник API Aspose.Slides для C++
description: Записывает указанный символ в поток.
type: docs
weight: 40
url: /ru/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) метод

Записывает указанный символ в поток.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char_t | Значение для записи |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) метод

Записывает указанный поддиапазон символов из заданного массива символов в поток.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Массив, содержащий символы для записи |
| index | **int32_t** | Нулевой индекс **buffer**, в котором начинается поддиапазон для записи |
| count | **int32_t** | Количество символов в поддиапазоне для записи |

## StringWriter::Write(const String\&) метод

Записывает указанную строку в поток.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Строка для записи |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [StringWriter](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)