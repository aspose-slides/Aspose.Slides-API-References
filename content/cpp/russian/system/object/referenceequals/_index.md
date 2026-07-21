---
title: ReferenceEquals()
second_title: Aspose.Slides для C++ API справочник
description: "Специализация Object::ReferenceEquals для случая строки и nullptr."
type: docs
weight: 261
url: /ru/system/object/referenceequals/
---
## Object::ReferenceEquals(String const&, std::nullptr_t) метод


Специализация [Object::ReferenceEquals](./) для случая строки и nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | [String](../../string/) const& | [String](../../string/) для сравнения с nullptr. |

### Возвращаемое значение

true, если строка равна null, иначе false.

## Object::ReferenceEquals(String const&, String const&) метод


Специализация [Object::ReferenceEquals](./) для случая строк.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str1 | [String](../../string/) const& | Первая строка для сравнения. |
| str2 | [String](../../string/) const& | Вторая строка для сравнения. |

### Возвращаемое значение

true, если строки совпадают, иначе false.

## Object::ReferenceEquals(ptr const&, ptr const&) метод


Сравнивает объекты по ссылке.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | [ptr](../ptr/) const& | Первый указатель для сравнения. |
| objB | [ptr](../ptr/) const& | Второй указатель для сравнения. |

### Возвращаемое значение

True, если указатели совпадают, иначе false.

## Object::ReferenceEquals(T const&, T const&) метод


Сравнивает объекты по ссылке.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип объектов для сравнения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | T const& | Первый объект для сравнения. |
| objB | T const& | Второй объект для сравнения. |

### Возвращаемое значение

True, если адреса объектов совпадают, иначе false.

## Object::ReferenceEquals(T const&, std::nullptr_t) метод


Сравнивает по ссылке объект значимого типа с nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип объекта для сравнения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | T const& | Первый объект для сравнения. |

### Возвращаемое значение

Всегда возвращает false, так как значения типов не могут быть нулевыми.

## См. также

* Typedef [ptr](../ptr/)
* Класс [String](../../string/)
* Класс [Object](../)
* Структура [IsSmartPtr](../../issmartptr/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)