---
title: operator<()
second_title: Aspose.Slides для C++ справочник API
description: 
type: docs
weight: 2068
url: /ru/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) функция




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) функция




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) функция


Всегда возвращает false.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) функция


Определяет, является ли указанное значение меньше значения, представленного указанным объектом [Nullable](../nullable/), применяя [operator<()](./) к этим значениям.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип первого сравниваемого значения |
| T2 | Базовый тип объекта [Nullable](../nullable/), представляющего второе сравниваемое значение |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| some | const T1\& | Константная ссылка на значение, которое будет использоваться в качестве первого сравниваемого |
| other | const [Nullable](../nullable/)\<T2\>\& | Константная ссылка на объект [Nullable](../nullable/), представление значения которого будет использоваться в качестве второго сравниваемого |

### Возвращаемое значение

True, если первый сравниваемый меньше второго сравниваемого, иначе - false

## System::operator<(std::nullptr_t, TimeSpan) функция




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## Смотрите также

* Класс [DateTime](../datetime/)
* Класс [DateTimeOffset](../datetimeoffset/)
* Класс [Nullable](../nullable/)
* Класс [TimeSpan](../timespan/)
* Структура [IsNullable](../isnullable/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)