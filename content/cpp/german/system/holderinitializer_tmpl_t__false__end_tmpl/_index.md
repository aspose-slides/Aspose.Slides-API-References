---
title: HolderInitializer< T, false >
second_title: Aspose.Slides für C++ API-Referenz
description: HolderInitializer-Spezialisierung für den Fall, dass T ein Werttyp ist. Der Nutzungskontext erlaubt das Zurückgeben einer Referenz auf temporäre Objekte, da garantiert ist, dass die Instanz vom Aufrufer kopiert wird. Daher wird diese Spezialisierung nur als Stub verwendet und tut nichts.
type: docs
weight: 1652
url: /de/system/holderinitializer_tmpl_t__false__end_tmpl/
---
## HolderInitializer< T, false > struct


[HolderInitializer](../holderinitializer/) Spezialisierung für den Fall, dass T ein Werttyp ist., Der Nutzungskontext erlaubt das Zurückgeben einer Referenz auf temporäre Objekte, da garantiert ist, dass die Instanz vom Aufrufer kopiert wird. So wird diese Spezialisierung nur als Stub verwendet und tut nichts.

```cpp
template<typename T>class HolderInitializer< T, false >
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) |  |
|  [HolderInitializer](./holderinitializer/)(T\&) |  |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) |  |
## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)