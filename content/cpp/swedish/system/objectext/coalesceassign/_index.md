---
title: CoalesceAssign()
second_title: Aspose.Slides för C++ API-referens
description: Implementering av '??='-operatorns översättning.
type: docs
weight: 183
url: /sv/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) metod

Implementering av '??='-operatorns översättning.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T0 | Värdetyp för vänster sida. |
| T1 | Typ av lambda som kapslar in RHS-uttrycket. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T0\& | Värde på vänster sida. |
| func | T1 | RHS-uttryck. |

### Returvärde

Om värdet på vänster sida inte är null returneras det, annars beräknas RHS-uttrycket och resultatet returneras.

## Se också

* Klass [ObjectExt](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)