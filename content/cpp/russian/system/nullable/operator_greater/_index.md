---
title: operator>()
second_title: Справочник API Aspose.Slides для C++
description: Всегда возвращает false.
type: docs
weight: 157
url: /ru/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const метод

Всегда возвращает false.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const метод

Определяет, превышает ли значение, представленное текущим объектом, указанное значение, применив [operator>()](./) к этим значениям.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип значения, с которым сравнивается |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const T1\& | Константная ссылка на значение, с которым сравнивается |

### Возвращаемое значение

True если значение, представленное текущим объектом, больше указанного значения, иначе — false

## Nullable::operator>(const Nullable\<T1\>\&) const метод

Определяет, превышает ли значение, представленное текущим объектом, значение, представленное указанным объектом [Nullable](../), применив [operator>()](./) к этим значениям.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Базовый тип объекта [Nullable](../), с которым сравнивают |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Константная ссылка на объект [Nullable](../), с которым сравнивают |

### Возвращаемое значение

True если значение, представленное текущим объектом, больше значения, представленного указанным объектом [Nullable](../), иначе — false

## См. также

* Класс [Nullable](../)
* Структура [IsNullable](../../isnullable/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)