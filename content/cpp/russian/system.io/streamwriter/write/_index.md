---
title: Write()
second_title: Справочник API Aspose.Slides для C++
description: Записывает указанный символ в поток.
type: docs
weight: 79
url: /ru/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) метод

Записывает указанный символ в поток.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char_t | Записываемый символ |

## StreamWriter::Write(const String\&) метод

Записывает указанную строку в поток.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Записываемая строка |

## StreamWriter::Write(const SharedPtr\<Object\>\&) метод

Записывает строковое представление указанного объекта в поток.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Записываемый объект |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) метод

Записывает все символы из указанного массива в поток.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Массив, содержащий символы для записи |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) метод

Записывает указанный подмассив UTF-16 символов из заданного массива символов в поток.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Массив, содержащий символы для записи |
| index | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается подмассив для записи |
| count | **int32_t** | Количество символов в подмассиве для записи; -1 указывает, что подмассив заканчивается в конце массива **buffer** |

## StreamWriter::Write(const char_t *) метод

Записывает указанную C-строку в поток.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const char_t * | Записываемая C-строка |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) метод

Записывает строковое представление указанного объекта в поток.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип объекта |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | Записываемый объект |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [StreamWriter](../)
* Класс [String](../../../system/string/)
* Класс [Object](../../../system/object/)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)