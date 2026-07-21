---
title: operator<=()
second_title: Aspose.Slides для C++: справочник API
description: Всегда возвращает false.
type: docs
weight: 196
url: /ru/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const method


Всегда возвращает false.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const method


Определяет, меньше ли или равно значение, представленное текущим объектом, указанному значению, применяя [operator<=()](./) к этим значениям.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T1 | The type of the value to compare with |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A constant reference to the value to compare with |

### Возвращаемое значение

True, если значение, представленное текущим объектом, меньше либо равно указанному значению, иначе — false

## Nullable::operator<=(const Nullable\<T1\>\&) const method


Определяет, меньше ли или равно значение, представленное текущим объектом, значению, представленному указанным объектом [Nullable](../), применяя [operator<=()](./) к этим значениям.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | A constant reference to the [Nullable](../) object to compare with |

### Возвращаемое значение

True, если значение, представленное текущим объектом, меньше либо равно значению, представленному указанным объектом [Nullable](../), иначе — false

## См. также

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)