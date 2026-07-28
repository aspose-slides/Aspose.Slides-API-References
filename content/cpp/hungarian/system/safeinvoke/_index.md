---
title: SafeInvoke()
second_title: Aspose.Slides C++ API referencia
description: A '?.' operátor fordításának megvalósítása.
type: docs
weight: 2653
url: /hu/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) function


A '?.' operátor lefordításának megvalósítása.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T0 | kifejezés típusa. |
| T1 | A 'WhenTrue' kifejezést becsomagoló lambda típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| expr | T0\&& | kifejezés értéke. |
| func | T1\&& | 'WhenTrue' kifejezést a funktornak kötve. |

### Visszatérési érték

Ha az expr értéke nem null, visszaadja a func-ot, amelyet az értékével első argumentumként hívnak, egyébként null-t ad vissza.

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)