---
title: operator+()
second_title: Aspose.Slides для C++ Справка по API
description: Оператор конкатенации строк.
type: docs
weight: 274
url: /ru/system/string/operator_plus/
---
## String::operator+(const String\&) const method


[String](../) оператор конкатенации.

```cpp
String System::String::operator+(const String &str) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) для добавления в конец текущей. |

### Возвращаемое значение

Конкатенированная строка.

## String::operator+(const T\&) const method


[String](../) конкатенация со строковым литералом или указателем на строку символов.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Одна из форм строкового литерала или указателя на строку символов. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg | const T\& | Объект для конкатенации с текущей строкой. |

### Возвращаемое значение

Конкатенированная строка.

## String::operator+(char_t) const method


```cpp
String System::String::operator+(char_t x) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | char_t | Символ для добавления. |

### Возвращаемое значение

[String](../) результат конкатенации.

## String::operator+(int) const method


```cpp
String System::String::operator+(int i) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | int | Целочисленное значение, преобразуемое в строку и добавляемое. |

### Возвращаемое значение

[String](../) результат конкатенации.

## String::operator+(uint32_t) const method


```cpp
String System::String::operator+(uint32_t i) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | **uint32_t** | Значение, преобразуемое в строку и добавляемое. |

### Возвращаемое значение

[String](../) результат конкатенации.

## String::operator+(double) const method


```cpp
String System::String::operator+(double d) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| d | **double** | Значение, преобразуемое в строку и добавляемое. |

### Возвращаемое значение

[String](../) результат конкатенации.

## String::operator+(int64_t) const method


```cpp
String System::String::operator+(int64_t v) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| v | **int64_t** | Значение, преобразуемое в строку и добавляемое. |

### Возвращаемое значение

[String](../) результат конкатенации.

## String::operator+(const T\&) const method


```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | тип указателя. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) для преобразования в строку с помощью вызова [ToString()](../tostring/) и добавления к текущей строке. |

### Возвращаемое значение

[String](../) результат конкатенации.

## String::operator+(const T\&) const method


```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип значения, для которого вызывается [ToString()](../tostring/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) для преобразования в строку с помощью вызова [ToString()](../tostring/) и добавления к текущей строке. |

### Возвращаемое значение

[String](../) результат конкатенации.

## String::operator+(T) const method


```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип значения для конкатенации со строкой. Должен быть bool |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) значение для преобразования в строку и добавления. |

### Возвращаемое значение

[String](../) результат конкатенации.

## См. также

* Класс [String](../)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)