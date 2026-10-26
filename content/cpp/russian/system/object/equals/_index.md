---
title: Equals()
second_title: Aspose.Slides для C++ справочник API
description: Сравнивает объекты, используя семантику C# Object.Equals.
type: docs
weight: 157
url: /ru/system/object/equals/
---
## Object::Equals(ptr) метод

Сравнивает объекты, используя семантику C# [Object.Equals](./).

```cpp
virtual bool System::Object::Equals(ptr obj)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) для сравнения с текущим объектом. |

### Возвращаемое значение

Возвращает true, если объекты считаются равными, и false в противном случае.

## Object::Equals(T1 const\&, T2 const\&) метод

Сравнивает объекты ссылочного типа в стиле C#.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип первого объекта для сравнения. |
| T2 | Тип второго объекта для сравнения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | T1 const\& | Первый объект для сравнения. |
| objB | T2 const\& | Второй объект для сравнения. |

### Возвращаемое значение

Возвращает true, если объекты совпадают либо по ссылке, либо семантически (по сравнению, подобному [Object.Equals](./)), иначе false.

## Object::Equals(T1 const\&, T2 const\&) метод

Сравнивает объекты значимого типа в стиле C#.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип первого объекта для сравнения. |
| T2 | Тип второго объекта для сравнения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | T1 const\& | Первый объект для сравнения. |
| objB | T2 const\& | Второй объект для сравнения. |

### Возвращаемое значение

Возвращает true, если объекты считаются равными с помощью доступного оператора равенства, иначе false.

## Object::Equals(float const\&, float const\&) метод

Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | **float** const\& | LHS значение числа с плавающей запятой. |
| objB | **float** const\& | RHS значение числа с плавающей запятой. |

### Возвращаемое значение

Возвращает true, если **objA** и **objB** оба NaN или равны, иначе false.

## Object::Equals(double const\&, double const\&) метод

Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | **double** const\& | LHS значение числа с плавающей запятой. |
| objB | **double** const\& | RHS значение числа с плавающей запятой. |

### Возвращаемое значение

Возвращает true, если **objA** и **objB** оба NaN или равны, иначе false.

## См. также

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)