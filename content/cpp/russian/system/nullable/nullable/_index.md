---
title: Nullable()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт экземпляр, представляющий значение null.
type: docs
weight: 1
url: /ru/system/nullable/nullable/
---
## Nullable::Nullable() конструктор

Создаёт экземпляр, представляющий значение null.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) конструктор

Создаёт экземпляр, представляющий null.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) конструктор

Создаёт экземпляр класса [Nullable](../), представляющий указанное значение, преобразованное (при необходимости) к типу T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип указанного значения |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T1\& | Константная ссылка на значение, которое будет представлено новым созданным объектом [Nullable](../) |

## Nullable::Nullable(const Nullable\<T1\>\&) конструктор

Создаёт экземпляр, представляющий значение, представляемое указанным объектом [Nullable](../). Указанный nullable-объект может представлять значение другого типа, чем базовый тип создаваемого экземпляра; в этом случае представляемое значение преобразуется к типу T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип значения, представленного указанным объектом [Nullable](../) |

## См. также

* Класс [Nullable](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)