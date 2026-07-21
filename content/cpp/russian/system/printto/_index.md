---
title: PrintTo()
second_title: Справочник API Aspose.Slides для C++
description: Печатает значение в ostream. В основном используется для отладки.
type: docs
weight: 2120
url: /ru/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) функция

Выводит значение в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```
## System::PrintTo(DateTimeOffset, std::ostream *) функция

Выводит значение в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```
## System::PrintTo(const Decimal\&, ::std::ostream *) функция

Записывает значение, представляемое указанным объектом, в указанный поток вывода.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | Объект [Decimal](../decimal/) для вывода в поток |
| os | ::std::ostream * | Поток, в который выводится указанный объект |

## System::PrintTo(const Details_Exception\&, std::ostream *) функция

Выводит значение в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```
## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) функция

Выводит значение в ostream. В основном используется для отладки.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```
## System::PrintTo(const Guid\&, std::ostream *) функция

Выводит значение в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```
## System::PrintTo(const Nullable\<T\>\&, std::ostream *) функция

Выводит значение в ostream. В основном используется для отладки.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```
## System::PrintTo(const System::Object\&, std::ostream *) функция

Выводит значение в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```
## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) функция

Выводит значение в ostream. В основном используется для отладки.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```
## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) функция

Выводит значение в ostream. В основном используется для отладки.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```
## System::PrintTo(const System::String\&, std::ostream *) функция

Выводит строку в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [System::String](../string/)\& | для вывода. |
| os | std::ostream * | целевой ostream. |

## System::PrintTo(TimeSpan, std::ostream *) функция

Выводит значение в ostream. В основном используется для отладки.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```
## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) функция

Выводит значение в ostream. В основном используется для отладки.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```
## См. также

* Класс [DateTime](../datetime/)
* Класс [DateTimeOffset](../datetimeoffset/)
* Класс [Decimal](../decimal/)
* Класс [Details_Exception](../details_exception/)
* Класс [ExceptionWrapper](../exceptionwrapper/)
* Класс [Guid](../guid/)
* Класс [Nullable](../nullable/)
* Класс [Object](../object/)
* Класс [SmartPtr](../smartptr/)
* Класс [String](../string/)
* Класс [TimeSpan](../timespan/)
* Класс [WeakPtr](../weakptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)