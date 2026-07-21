---
title: Write()
second_title: Aspose.Slides для C++ — справочник API
description: Записывает строковое представление указанного объекта в поток.
type: docs
weight: 105
url: /ru/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) метод


Записывает строковое представление указанного объекта в поток.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Объект для записи |

## TextWriter::Write(bool) метод


Записывает строковое представление указанного логического значения в поток.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **bool** | Значение для записи |

## TextWriter::Write(char_t) метод


Записывает указанный символ в поток.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char_t | Значение для записи |

## TextWriter::Write(Decimal) метод


Записывает строковое представление указанного [Decimal](../../../system/decimal/) объекта в поток.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | Объект для записи |

## TextWriter::Write(double) метод


Записывает строковое представление указанного значения двойной точности в поток.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **double** | Значение для записи |

## TextWriter::Write(int) метод


Записывает строковое представление указанного 32-битного целочисленного значения в поток.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение для записи |

## TextWriter::Write(int64_t) метод


Записывает строковое представление указанного 64-битного целочисленного значения в поток.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **int64_t** | Значение для записи |

## TextWriter::Write(float) метод


Записывает строковое представление указанного значения одинарной точности с плавающей точкой в поток.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **float** | Значение для записи |

## TextWriter::Write(const String\&) метод


Записывает указанную строку в поток.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Строка для записи |

## TextWriter::Write(uint32_t) метод


Записывает строковое представление указанного беззнакового 32-битного целочисленного значения в поток.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **uint32_t** | Значение для записи |

## TextWriter::Write(uint64_t) метод


Записывает строковое представление указанного беззнакового 64-битного целочисленного значения в поток.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **uint64_t** | Значение для записи |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) метод


Записывает все символы из указанного массива в поток.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Массив, содержащий символы для записи |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) метод


Записывает указанный поддиапазон символов UTF-16 из указанного массива символов в поток.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Массив, содержащий символы для записи |
| index | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается записываемый поддиапазон |
| count | **int32_t** | Количество символов в поддиапазоне для записи; -1 указывает, что поддиапазон заканчивается в конце массива **buffer** |

## TextWriter::Write(const char_t *) метод


Записывает указанную C-строку в поток.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка для записи |

## TextWriter::Write(const TypeInfo\&) метод


Записывает строковое представление указанного [TypeInfo](../../../system/typeinfo/) объекта в поток.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | Объект для записи |

## TextWriter::Write(const String\&, const TArgs\&...) метод


Записывает указанные значения, отформатированные согласно указанному формату, в поток.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TArgs | Список типов записываемых значений |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Строковый формат |
| args | const TArgs\&... | Значения для записи |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [Object](../../../system/object/)
* Класс [TextWriter](../)
* Класс [Decimal](../../../system/decimal/)
* Класс [String](../../../system/string/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)