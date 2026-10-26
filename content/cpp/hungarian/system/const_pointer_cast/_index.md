---
title: const_pointer_cast()
second_title: Aspose.Slides for C++ API Referencia
description: Átalakítja a smart pointereket a const_cast használatával.
type: docs
weight: 2939
url: /hu/system/const_pointer_cast/
---
## System::const_pointer_cast(SmartPtr\<X\> const\&) függvény

Átalakítja a smart pointereket a const_cast használatával.

```cpp
template<class Y,class X> SmartPtr<Y> System::const_pointer_cast(SmartPtr<X> const &x)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| X | A forrás pointer által mutatott típus. |
| Y | A cél pointer által mutatott típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Forrás pointer. |

### Visszatérési érték

Pointer a cast után.

## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)