---
title: MakeScopeGuard()
second_title: Aspose.Slides C++ API referencia
description: Gyári függvény, amely a ScopedGuard osztály példányait hozza létre.
type: docs
weight: 2809
url: /hu/system/makescopeguard/
---
## System::MakeScopeGuard(F) függvény


Gyári függvény, amely a ScopedGuard osztály példányait hozza létre.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| The | a függvényobjektum típusa, amelyet a létrehozott ScopedGuard objektum hív meg |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| f | F | A függvényobjektum, amelyet a ScopedGuard osztály konstruktorának kell átadni. |

### Visszatérési érték

Új példány a ScopedGuard osztályból

## Lásd még

* Struktúra [ScopeGuard](../scopeguard/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)