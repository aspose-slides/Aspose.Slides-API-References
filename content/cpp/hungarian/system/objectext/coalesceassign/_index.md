---
title: CoalesceAssign()
second_title: Aspose.Slides C++ API referencia
description: A '??=' operátor lefordításának megvalósítása.
type: docs
weight: 183
url: /hu/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) metódus


A '??=' operátor lefordítása megvalósítása.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T0 | LHS érték típusa. |
| T1 | RHS kifejezést tartalmazó lambda típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | T0\& | LHS érték. |
| func | T1 | RHS kifejezés. |

### Visszatérési érték

Ha a LHS érték nem null, visszaadja a LHS-t, egyébként kiszámítja a RHS kifejezést és visszaadja az eredményt.

## Lásd még

* Osztály [ObjectExt](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)