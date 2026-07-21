---
title: WriteLine()
second_title: Справочник API Aspose.Slides для C++
description: Записывает символы завершения строки в поток.
type: docs
weight: 92
url: /ru/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() метод

Записывает символы завершения строки в поток.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) метод

Записывает указанную строку, за которой следуют символы завершения строки, в поток.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Строка для записи |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) метод

Записывает строковое представление указанного объекта, за которым следуют символы завершения строки, в поток.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Объект для записи |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) метод

Записывает все символы из указанного массива, за которыми следуют символы завершения строки, в поток.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Массив, содержащий символы для записи |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) метод

Записывает указанный поддиапазон UTF-16 символов из указанного массива символов, за которым следуют символы завершения строки, в поток.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Массив, содержащий символы для записи |
| index | **int32_t** | Нулевой-базовый индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | **int32_t** | Количество символов в поддиапазоне для записи; -1 указывает, что поддиапазон заканчивается в конце массива **buffer** |

## StreamWriter::WriteLine(const char_t *) метод

Записывает указанную C-строку, за которой следуют символы завершения строки, в поток.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const char_t * | C-строка для записи |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) метод

Записывает строковое представление указанного объекта, за которым следуют символы завершения строки, в поток.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип объекта |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | Объект для записи |

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)