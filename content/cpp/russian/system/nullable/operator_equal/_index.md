---
title: operator=()
second_title: Aspose.Slides для C++ справки API
description: Назначает null текущему объекту.
type: docs
weight: 14
url: /ru/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) метод

Назначает null текущему объекту.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```

### Возвращаемое значение

Объект [Nullable](../), представляющий значение null.

## Nullable::operator=(const T1\&) метод

Заменяет текущее представляемое объектом значение указанным.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| The | тип нового значения, которое будет представлено текущим объектом |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const T1\& | Новое значение, которое будет представлено текущим объектом |

### Возвращаемое значение

Ссылка на себя

## Nullable::operator=(const Nullable\<T1\>\&) метод

Заменяет текущее представляемое объектом значение указанным.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| The | тип нового значения, которое будет представлено текущим объектом |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | Новое значение, которое будет представлено текущим объектом |

### Возвращаемое значение

Ссылка на себя

## См. также

* Класс [Nullable](../)
* Структура [IsNullable](../../isnullable/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)