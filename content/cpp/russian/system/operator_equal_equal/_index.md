---
title: operator==()
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 2016
url: /ru/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) функция




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) функция




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) функция




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) функция


Определяет, представляет ли указанный объект [Nullable](../nullable/) значение, равное null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | std::nullptr_t | Константная ссылка на объект [Nullable](../nullable/) для проверки |

### Возвращаемое значение

True если указанный объект представляет значение null, иначе false

## System::operator==(const T1\&, const Nullable\<T2\>\&) функция


Определяет, равно ли указанное значение значению, представленному указанным объектом [Nullable](../nullable/) путем применения [operator==()](./) к этим значениям.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип первого сравниваемого значения |
| T2 | Базовый тип объекта [Nullable](../nullable/), представляющего второе сравниваемое значение |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| some | const T1\& | Константная ссылка на значение, которое будет использовано как первый сравниваемый |
| other | const [Nullable](../nullable/)\<T2\>\& | Константная ссылка на объект [Nullable](../nullable/), значение которого будет использовано как второй сравниваемый |

### Возвращаемое значение

True если сравниваемые значения равны, иначе false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) функция


Сравнение на равенство двух умных указателей.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| X | Тип объекта, на который указывает первый указатель. |
| Y | Тип объекта, на который указывает второй указатель. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Первый указатель для сравнения. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Второй указатель для сравнения. |

### Возвращаемое значение

True если указатели совпадают, иначе false.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) функция


Проверяет, является ли умный указатель null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| X | Тип объекта, на который указывает указатель. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | std::nullptr_t | Указатель для проверки. |

### Возвращаемое значение

True если указатель null, иначе false.

## System::operator==(const SmartPtr\<X\>\&, const Y *) функция


Сравнение на равенство умного указателя с простым (C) указателем.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| X | тип умного указателя. |
| Y | тип простого указателя. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | умный указатель для сравнения (слева). |
| y | const Y * | указатель для сравнения (справа). |

### Возвращаемое значение

True если указатели совпадают, иначе false.

## System::operator==(const X *, const SmartPtr\<Y\>\&) функция


Сравнение на равенство простого (C) указателя с умным указателем.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| X | тип простого указателя. |
| Y | тип умного указателя. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const X * | указатель для сравнения (справа). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | умный указатель для сравнения (слева). |

### Возвращаемое значение

True если указатели совпадают, иначе false.

## System::operator==(T const\&, std::nullptr_t) функция


Проверяет, является ли объект типа значения (переведённая структура C# и т.п.) null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип значения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | T const\& | [Object](../object/) для проверки. |

### Возвращаемое значение

True если объект null, иначе false.

## System::operator==(std::nullptr_t, T const\&) функция


Проверяет, является ли объект типа значения (переведённая структура C# и т.п.) null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип значения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) для проверки. |

### Возвращаемое значение

True если объект null, иначе false.

## System::operator==(Chars\&, const String\&) функция


[String](../string/) сравнение.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Chars | [String](../string/) тип литерала. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | Chars\& | [String](../string/) литерал для сравнения. |
| right | const [String](../string/)\& | [String](../string/) для сравнения. |

### Возвращаемое значение

true если строки совпадают, иначе false.

## System::operator==(T\&, const String\&) функция


[String](../string/) сравнение.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [String](../string/) тип указателя. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | T\& | [String](../string/) указатель для сравнения. |
| right | const [String](../string/)\& | [String](../string/) для сравнения. |

### Возвращаемое значение

true если строки совпадают, иначе false.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) функция


[Object](../object/) и сравнение со строкой.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) для преобразования в строку и сравнения. |
| right | const [String](../string/)\& | [String](../string/) для сравнения. |

### Возвращаемое значение

true если строковое представление объекта равно строке, иначе false.

## System::operator==(std::nullptr_t, const String\&) функция


Проверяет, является ли строка null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) для проверки. |

### Возвращаемое значение

true если строка null, иначе false.

## System::operator==(std::nullptr_t, TimeSpan) функция




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) функция


Определяет, равны ли URI, представленные текущим и указанным объектами.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Первый объект [Uri](../uri/) для сравнения |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Второй объект [Uri](../uri/) для сравнения |

### Возвращаемое значение

True если URI равны, иначе false

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)