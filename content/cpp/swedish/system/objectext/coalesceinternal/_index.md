---
title: CoalesceInternal()
second_title: Aspose.Slides för C++ API-referens
description: Implementering av '??'-operatorns översättning för icke-nullbara typer. Överlagring för fallet när RT2 kan konverteras till RT1.
type: docs
weight: 157
url: /sv/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) method

Implementering av '??'-operatorns översättning för icke-nullbara typer. Överlagring för fallet när RT2 kan konverteras till RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T0 | LHS-värdetyp. |
| T1 | Typ av lambda som kapslar RHS-uttrycket. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | RT1 | LHS-värde. |
| func | F | RHS-uttryck. |

### Returvärde

Om LHS-värdet inte är null returneras LHS, annars beräknas RHS-uttrycket och resultatet returneras.

## Se även

* Klass [ObjectExt](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)