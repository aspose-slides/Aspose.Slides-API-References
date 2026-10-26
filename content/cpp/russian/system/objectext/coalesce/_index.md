---
title: Coalesce()
second_title: Aspose.Slides для справочника API C++
description: Реализация перевода оператора '??' для типов, не допускающих null.
type: docs
weight: 170
url: /ru/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) метод

Реализация перевода оператора `??` для типов, не допускающих null.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T0 | Тип значения LHS. |
| T1 | Тип лямбда-выражения, инкапсулирующего выражение RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T0 | Значение LHS. |
| func | T1 | Выражение RHS. |

### Возвращаемое значение

Если значение LHS не равно null, возвращается LHS, иначе вычисляется выражение RHS и возвращается результат.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) метод

Реализация перевода оператора `??` для типов, допускающих null.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T0 | Тип значения LHS. |
| T1 | Тип лямбда-выражения, инкапсулирующего выражение RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | Значение LHS. |
| func | T1 | Выражение RHS. |

### Возвращаемое значение

Если значение LHS не равно null, возвращается LHS, иначе вычисляется выражение RHS и возвращается результат.

## See Also

* Класс [ObjectExt](../)
* Класс [Nullable](../../nullable/)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)