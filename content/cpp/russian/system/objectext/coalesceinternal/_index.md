---
title: CoalesceInternal()
second_title: Aspose.Slides для C++ справочник API
description: Реализация перевода оператора '??' для типов, не допускающих null. Перегрузка для случая, когда RT2 может быть преобразован к RT1.
type: docs
weight: 157
url: /ru/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) метод


Реализация перевода оператора '??' для типов, не допускающих null. Перегрузка для случая, когда RT2 может быть преобразован к RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T0 | Тип значения LHS. |
| T1 | Тип лямбда-выражения, инкапсулирующего выражение RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | RT1 | Значение LHS. |
| func | F | Выражение RHS. |

### Возвращаемое значение

Если значение LHS не равно null, возвращается LHS, в противном случае вычисляется выражение RHS и возвращается результат.

## См. также

* Класс [ObjectExt](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)