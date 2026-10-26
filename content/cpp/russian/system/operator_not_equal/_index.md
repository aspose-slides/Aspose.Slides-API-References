---
title: operator!=()
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 2029
url: /ru/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) функция




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) функция




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) функция




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) функция

Определяет, представляет ли указанный объект [Nullable](../nullable/) значение, которое не равно null.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | std::nullptr_t | Константная ссылка на объект [Nullable](../nullable/) для тестирования |

### Возвращаемое значение

true, если указанный объект представляет ненулевое значение, false в противном случае

## System::operator!=(const T1\&, const Nullable\<T2\>\&) функция

Определяет, не равна ли указанное значение значению, представленному указанным объектом [Nullable](../nullable/) путем применения [operator!=()](./) к этим значениям.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип первого сравниваемого значения |
| T2 | Базовый тип объекта [Nullable](../nullable/), представляющего второе сравниваемое значение |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| some | const T1\& | Константная ссылка на значение, которое будет использоваться в качестве первого сравниваемого |
| other | const [Nullable](../nullable/)\<T2\>\& | Константная ссылка на объект [Nullable](../nullable/), представляемое значение которого будет использоваться в качестве второго сравниваемого |

### Возвращаемое значение

true, если сравниваемые значения не равны, иначе - false

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) функция

Сравнивает два умных указателя на неравенство.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| X | Тип объекта, на который указывает первый указатель. |
| Y | Тип объекта, на который указывает второй указатель. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Первый указатель для сравнения. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Второй указатель для сравнения. |

### Возвращаемое значение

false, если указатели совпадают, иначе true.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) функция

Проверяет, что умный указатель не равен null.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| X | Тип объекта, на который указывает указатель. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Указатель для проверки. |

### Возвращаемое значение

false, если указатель равен null, иначе true.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) функция

Проверяет, что умный указатель не равен null.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| X | Тип объекта, на который указывает указатель. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | std::nullptr_t | Указатель для проверки. |

### Возвращаемое значение

false, если указатель равен null, иначе true.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) функция

Сравнение на неравенство умного указателя с простым (C) указателем.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| X | тип умного указателя. |
| Y | тип простого указателя. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | умный указатель для сравнения (слева). |
| y | const Y * | указатель для сравнения (справа). |

### Возвращаемое значение

false, если указатели совпадают, иначе true.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) функция

Сравнение на равенство умного указателя с простым (C) указателем.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| X | тип простого указателя. |
| Y | тип умного указателя. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const X * | указатель для сравнения (справа). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | умный указатель для сравнения (слева). |

### Возвращаемое значение

false, если указатели совпадают, иначе true.

## System::operator!=(Chars\&, const String\&) функция

[String](../string/) сравнение.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Chars | [String](../string/) тип литерала. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | Chars\& | [String](../string/) литерал для сравнения. |
| right | const [String](../string/)\& | [String](../string/) для сравнения. |

### Возвращаемое значение

false, если строки совпадают, иначе true.

## System::operator!=(T\&, const String\&) функция

[String](../string/) сравнение.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [String](../string/) тип указателя. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | T\& | [String](../string/) указатель для сравнения. |
| right | const [String](../string/)\& | [String](../string/) для сравнения. |

### Возвращаемое значение

false, если строки совпадают, иначе true.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) функция

[Object](../object/) и сравнение со строкой.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) для преобразования в строку и сравнения. |
| right | const [String](../string/)\& | [String](../string/) для сравнения. |

### Возвращаемое значение

false, если строковое представление объекта равно строке, иначе true.

## System::operator!=(std::nullptr_t, const String\&) функция

Проверяет, является ли строка null.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) для проверки. |

### Возвращаемое значение

false, если строка null, иначе true.

## System::operator!=(std::nullptr_t, TimeSpan) функция




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) функция

Определяет, не равны ли URI, представленные текущим и указанным объектами.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Первый [Uri](../uri/) объект для сравнения |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Второй [Uri](../uri/) объект для сравнения |

### Возвращаемое значение

true, если URI не равны, иначе - false

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