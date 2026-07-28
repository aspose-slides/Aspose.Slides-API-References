---
title: MakeSharedPtr()
second_title: Aspose.Slides for C++ API Referenciája
description: Átalakítja a nyers mutatót okos pointerré.
type: docs
weight: 2900
url: /hu/system/makesharedptr/
---
## System::MakeSharedPtr(X *) függvény

Átalakítja a nyers mutatót okos pointerré.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| X | Pointee típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| p | X * | Nyers mutató az objektumra. |

### Visszatérési érték

Megosztott okos pointer az objektumra.

## System::MakeSharedPtr(const X *) függvény

Átalakítja a nyers mutatót okos pointerré. Túlterhelés konstans mutatókhoz. Hasznos például, ha a 'this' változót C# metódusokban használják, amelyek const-ként vannak lefordítva.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| X | Pointee típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| p | const X * | Nyers mutató az objektumra. |

### Visszatérési érték

Megosztott okos pointer az objektumra.

## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)