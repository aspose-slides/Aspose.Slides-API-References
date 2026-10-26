---
title: SafeInvoke()
second_title: Aspose.Slides для C++ справочника API
description: Реализация трансляции оператора '?.'.
type: docs
weight: 2614
url: /ru/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) функция

Реализация трансляции оператора '?.'.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T0 | тип выражения. |
| T1 | Тип лямбда-выражения, инкапсулирующего выражение 'WhenTrue'. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| expr | T0\&& | значение выражения. |
| func | T1\&& | выражение 'WhenTrue', привязанное к функтору. |

### Возвращаемое значение

Если значение expr не равно null, возвращает вызов func с его значением в качестве первого аргумента, иначе возвращает null.

## См. также

* Namespace [System](../)
* Library [Aspose.Slides](../../)