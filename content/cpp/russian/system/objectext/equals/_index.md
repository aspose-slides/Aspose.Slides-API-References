---
title: Equals()
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 14
url: /ru/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) метод




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) метод


Подстановка для вызовов C# [Object.Equals](../../object/equals/) работает с любым типом в C++. Перегрузка для типов умных указателей.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### Возвращаемое значение

True, если объекты считаются равными, иначе false.

## ObjectExt::Equals(T, const T2\&) метод


Подстановка для вызовов C# [Object.Equals](../../object/equals/) работает с любым типом в C++. Перегрузка для структурных типов.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T | First object. |
| another | const T2\& | Second object. |

### Возвращаемое значение

True, если объекты считаются равными, иначе false.

## ObjectExt::Equals(const T\&, const T2\&) метод


Подстановка для вызовов C# [Object.Equals](../../object/equals/) работает с любым типом в C++. Перегрузка для скалярных типов.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### Возвращаемое значение

True, если объекты считаются равными, иначе false.

## ObjectExt::Equals(const char_t(&), String) метод


Подстановка для вызовов C# [Object.Equals](../../object/equals/) работает с любым типом в C++. Перегрузка для строковых литералов с строковым сравнением.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| N | [String](../../string/) literal size. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) literal. |
| another | [String](../../string/) | [String](../../string/). |

### Возвращаемое значение

True, если строки совпадают, иначе false.

## ObjectExt::Equals(const float\&, const float\&) метод


Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const **float**\& | LHS floating point value. |
| another | const **float**\& | RHS floating point value. |

### Возвращаемое значение

True, если **obj** и **another** оба NaN или равны, иначе false.

## ObjectExt::Equals(const double\&, const double\&) метод


Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const **double**\& | LHS floating point value. |
| another | const **double**\& | RHS floating point value. |

### Возвращаемое значение

True, если **obj** и **another** оба NaN или равны, иначе false.

## См. также

* Класс [ObjectExt](../)
* Класс [String](../../string/)
* Структура [IsExceptionWrapper](../../isexceptionwrapper/)
* Структура [IsSmartPtr](../../issmartptr/)
* Простой имён [System](../../)
* Библиотека [Aspose.Slides](../../../)