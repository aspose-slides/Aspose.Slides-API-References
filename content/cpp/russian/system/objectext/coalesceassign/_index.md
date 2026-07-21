---
title: CoalesceAssign()
second_title: Aspose.Slides для C++ справочник API
description: Реализация оператора '??='.
type: docs
weight: 183
url: /ru/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) метод

Реализация оператора '??='.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T0 | Тип LHS-значения. |
| T1 | Тип лямбда-выражения, инкапсулирующего RHS-выражение. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T0\& | Значение LHS. |
| func | T1 | RHS-выражение. |

### Возвращаемое значение

Если значение LHS не равно null, возвращается LHS, иначе вычисляется выражение RHS и возвращается результат.

## Смотрите также

* Класс [ObjectExt](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)