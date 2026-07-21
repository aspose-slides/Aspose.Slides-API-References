---
title: operator-()
second_title: Aspose.Slides для C++ справочник API
description: Вычитает nullable и значения, указывающие на null.
type: docs
weight: 222
url: /ru/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const метод


Вычитает nullable и значения, указывающие на null.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип правого операнда, должен быть nullptr_t. |

### Возвращаемое значение

Пустой объект [Nullable](../).

## Nullable::operator-(const T1\&) const метод


Вычитает nullable и значения, не допускающие null.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип правого операнда. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const T1\& | значение для вычитания. |

### Возвращаемое значение

Результат вычитания.

## Nullable::operator-(const Nullable\<T1\>\&) const метод


Вычитает nullable значения.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип правого операнда. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | значение для вычитания. |

### Возвращаемое значение

Результат вычитания.

## См. также

* Класс [Nullable](../)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)