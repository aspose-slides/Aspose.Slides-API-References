---
title: operator-()
second_title: Справочник API Aspose.Slides для C++
description: Вычисляет количество дней между двумя днями недели.
type: docs
weight: 2146
url: /ru/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) функция


Вычисляет количество дней между двумя днями недели.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | Уменьшаемое |
| b | [DayOfWeek](../dayofweek/) | Вычитаемое |

### Возвращаемое значение

Количество дней между будними днями **a** и **b**; возвращаемое значение будет отрицательным, если *проходит* после ****

## System::operator-(const T\&, const Decimal\&) функция


Возвращает новый экземпляр класса [Decimal](../decimal/), представляющий значение, которое является результатом вычитания значения, представленного указанным объектом [Decimal](../decimal/), из указанного значения.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const T\& | Значение, из которого вычитают |
| d | const [Decimal](../decimal/)\& | Объект [Decimal](../decimal/), представляющий вычитаемое значение |

### Возвращаемое значение

Новый экземпляр класса [Decimal](../decimal/), представляющий значение, которое является результатом вычитания значения, представленного **d**, из **x**.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) функция


Отключает все обратные вызовы в правом делегате от конца списка обратных вызовов левого делегата.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Делегат, из которого будут удалены обратные вызовы. |
| rhv | MulticastDelegate\<T\> | Делегат, чьи обратные вызовы будут удалены. |

### Возвращаемое значение

Возвращает делегат, содержащий обратные вызовы левого значения, но без обратных вызовов правого значения.

## System::operator-(const T1\&, const Nullable\<T2\>\&) функция


Вычитает ненулевые и nullable значения.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип левого операнда. |
| T2 | Тип правого операнда. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| some | const T1\& | Левый операнд. |
| other | const [Nullable](../nullable/)\<T2\>\& | Правый операнд. |

### Возвращаемое значение

Результат вычитания.

## См. также

* Enum [DayOfWeek](../dayofweek/)
* Класс [Decimal](../decimal/)
* Класс [Nullable](../nullable/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)