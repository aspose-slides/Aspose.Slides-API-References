---
title: operator+=()
second_title: Aspose.Slides для C++ справки API
description: Сбрасывает текущий объект, чтобы он представлял null-значение.
type: docs
weight: 235
url: /ru/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) метод


Сбрасывает текущий объект, чтобы он представлял null-значение.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```


### Возвращаемое значение

Копия текущего объекта

## Nullable::operator+=(const T1\&) метод


Применяет [operator+=()](./) к значению, представленному текущим объектом, используя указанное значение в качестве аргумента справа.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T1 | Тип значения, используемого в качестве правой части [operator+=()](./) |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Константная ссылка на значение, которое используется в качестве правой части [operator+=()](./), применяемого к значению, представленному текущим объектом. |

### Возвращаемое значение

Ссылка на текущий объект

## Nullable::operator+=(const Nullable\<T1\>\&) метод


Применяет [operator+=()](./) к значению, представленному текущим объектом, используя значение, представленное указанным объектом [Nullable](../), в качестве аргумента справа.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T1 | Базовый тип объекта [Nullable](../), значение которого используется в качестве аргумента справа для [operator+=()](./) |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Константная ссылка на объект [Nullable](../), значение которого используется в качестве правого аргумента [operator+=()](./), применяемого к значению, представленному текущим объектом. |

### Возвращаемое значение

Ссылка на текущий объект

## См. также

* Класс [Nullable](../)
* Структура [IsNullable](../../isnullable/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)