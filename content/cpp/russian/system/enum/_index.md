---
title: Enum
second_title: Справочник API Aspose.Slides для C++
description: Предоставляет методы, выполняющие некоторые операции над значениями типа enum. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом.
type: docs
weight: 1561
url: /ru/system/enum/
---
## Структура Enum

Предоставляет методы, выполняющие некоторые операции над значениями типа enum. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом.

```cpp
template<class E,class Guard>class Enum
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| E | Тип enum, значения которого обрабатывает класс |
| Guard | Аргумент типа сервиса, цель которого — гарантировать, что **E** является перечислимым типом |
## Методы

| Метод | Описание |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Выполняет арифметическое сравнение значений указанных констант перечисления. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Возвращает имя константы перечисления, имеющей указанное значение. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Возвращает имя константы перечисления, имеющей указанное значение. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Возвращает массив, содержащий имена всех членов перечисления **E**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Возвращает базовый тип перечисления. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Возвращает массив, содержащий все члены перечисления **E**. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Определяет, установлены ли указанные биты в битовом представлении указанного значения enum. |
| static **bool** [IsDefined](./isdefined/)(E) | Определяет, является ли указанное значение членом типа перечисления **E**. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Определяет, является ли указанное значение членом типа перечисления **T**. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Определяет, присутствует ли значение с указанным именем среди членов enum **E**. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Преобразует заданную строку в эквивалентную константу enum. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Пытается преобразовать указанную строку в эквивалентную константу enum. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Пытается преобразовать указанную строку в эквивалентную константу enum. |
## Типы-алиасы

| Тип | Описание |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Псевдоним базового типа перечисления. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)