---
title: operator+()
second_title: Aspose.Slides для справки API C++
description: Возвращает экземпляр класса Nullable<T>, созданный по умолчанию.
type: docs
weight: 209
url: /ru/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const метод

Возвращает экземпляр класса Nullable<T>, созданный по умолчанию.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const метод

Складывает nullable и non-nullable значения.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Right operand type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const T1\& | значение для добавления. |

### Возвращаемое значение

Результат сложения.

## Nullable::operator+(const Nullable\<T1\>\&) const метод

Складывает nullable значения.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Right operand type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | значение для добавления. |

### Возвращаемое значение

Результат сложения.

## Смотрите также

* Класс [Nullable](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)