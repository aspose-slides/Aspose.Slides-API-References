---
title: Write()
second_title: Справочник API Aspose.Slides для C++
description: Выводит строковое представление указанного объекта в стандартный поток вывода.
type: docs
weight: 1
url: /ru/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) метод


Выводит строковое представление указанного объекта в стандартный поток вывода.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип выводимого объекта |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) для вывода |

## Console::Write(bool) метод


Выводит строковое представление логического значения в стандартный поток вывода.

```cpp
static void System::Console::Write(bool value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **bool** | Значение для вывода |

## Console::Write(char_t) метод


Выводит указанное символьное значение в стандартный поток вывода.

```cpp
static void System::Console::Write(char_t value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char_t | Значение для вывода |

## Console::Write(const ArrayPtr\<char_t\>\&) метод


Выводит строковое представление указанного массива символов в стандартный поток вывода.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Массив для вывода |

## Console::Write(const Decimal\&) метод


Выводит строковое представление значения [Decimal](../../decimal/) в стандартный поток вывода.

```cpp
static void System::Console::Write(const Decimal &value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Значение для вывода |

## Console::Write(double) метод


Выводит строковое представление значения типа double в стандартный поток вывода.

```cpp
static void System::Console::Write(double value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **double** | Значение для вывода |

## Console::Write(float) метод


Выводит строковое представление значения типа float в стандартный поток вывода.

```cpp
static void System::Console::Write(float value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **float** | Значение для вывода |

## Console::Write(int32_t) метод


Выводит строковое представление 32-битного целого значения в стандартный поток вывода.

```cpp
static void System::Console::Write(int32_t value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **int32_t** | Значение для вывода |

## Console::Write(int64_t) метод


Выводит строковое представление 64-битного целого значения в стандартный поток вывода.

```cpp
static void System::Console::Write(int64_t value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **int64_t** | Значение для вывода |

## Console::Write(const String\&) метод


Выводит указанный объект строки в стандартный поток вывода.

```cpp
static void System::Console::Write(const String &value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Объект строки для вывода |

## Console::Write(const char_t *) метод


Выводит указанную C-строку в стандартный поток вывода.

```cpp
static void System::Console::Write(const char_t *value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка для вывода |

## Console::Write(const TypeInfo\&) метод


Выводит строковое представление значения [TypeInfo](../../typeinfo/) в стандартный поток вывода.

```cpp
static void System::Console::Write(const TypeInfo &value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | Значение для вывода |

## Console::Write(uint32_t) метод


Выводит строковое представление беззнакового 32-битного целого значения в стандартный поток вывода.

```cpp
static void System::Console::Write(uint32_t value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **uint32_t** | Значение для вывода |

## Console::Write(uint64_t) метод


Выводит строковое представление беззнакового 64-битного целого значения в стандартный поток вывода.

```cpp
static void System::Console::Write(uint64_t value)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **uint64_t** | Значение для вывода |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) метод


Выводит строковое представление указанного диапазона указанного массива символов в стандартный поток вывода.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Массив символов |
| index | **int32_t** | Индекс в массиве, с которого начинается диапазон для вывода |
| count | **int32_t** | Количество элементов в диапазоне для вывода |

## Console::Write(const String\&, Args\&&...) метод


Выводит строковое представление указанных аргументов, отформатированных в соответствии с указанным форматом, в стандартный поток вывода.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| The | типы выводимых значений |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | const [String](../../string/)\& | Строковый формат |
| args | Args\&&... | Значения для вывода |

## Console::Write(const char *) метод




```cpp
static void System::Console::Write(const char *)=delete
```

## Смотрите также

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Console](../)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)