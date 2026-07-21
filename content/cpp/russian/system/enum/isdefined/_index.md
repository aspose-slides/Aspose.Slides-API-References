---
title: IsDefined()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, является ли указанное значение членом перечисления типа E.
type: docs
weight: 27
url: /ru/system/enum/isdefined/
---
## Enum::IsDefined(E) method


Определяет, является ли указанное значение членом перечисления типа **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | E | Значение для проверки |

### Возвращаемое значение

True, если **value** является членом перечисления **E**, иначе - false

## Enum::IsDefined(T) method


Определяет, является ли указанное значение членом перечисления типа **T**.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T | Значение для проверки |

### Возвращаемое значение

True, если **value** является членом перечисления **T**, иначе - false

## Enum::IsDefined(const String\&) method


Определяет, присутствует ли значение с указанным именем среди членов перечисления **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../string/)\& | Имя для проверки |

### Возвращаемое значение

True, если существует член перечисления **E** с указанным именем.

## См. также

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)