---
title: Coalesce()
second_title: Aspose.Slides för C++ API-referens
description: Implementering av '??'-operatorns översättning för icke-nullbara typer.
type: docs
weight: 170
url: /sv/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) metod

Implementering av '??'-operatorns översättning för icke-nullbara typer.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T0 | Typ av LHS-värde. |
| T1 | Typ av lambda som kapslar RHS-uttrycket. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T0 | LHS-värde. |
| func | T1 | RHS-uttryck. |

### Returvärde

Om LHS-värdet inte är null, returneras LHS, annars beräknas RHS-uttrycket och resultatet returneras.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) metod

Implementering av '??'-operatorns översättning för nullbara typer.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T0 | Typ av LHS-värde. |
| T1 | Typ av lambda som kapslar RHS-uttrycket. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | LHS-värde. |
| func | T1 | RHS-uttryck. |

### Returvärde

Om LHS-värdet inte är null, returneras LHS, annars beräknas RHS-uttrycket och resultatet returneras.

## Se också

* Klass [ObjectExt](../)
* Klass [Nullable](../../nullable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)