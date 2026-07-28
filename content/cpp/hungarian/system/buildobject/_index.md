---
title: BuildObject()
second_title: Aspose.Slides C++ API referenciája
description: Objektum létrehozása megosztott tulajdonjoggal.
type: docs
weight: 2250
url: /hu/system/buildobject/
---
## System::BuildObject(Args\&&...) függvény

Objektum létrehozása megosztott tulajdonjoggal.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A létrehozandó objektum típusa |
| Args | Az objektum konstrukciójának argumentumtípusai |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | Args\&&... | Az objektum konstruktorának továbbadandó argumentumok |

### Visszatérési érték

ObjectBuilder a megosztott mutató konstrukcióhoz konfigurálva

## Megjegyzések

Létrehoz egy SharedPtr<T>-t és visszaad egy építőt hozzá
[Object](../object/) a konstrukciót be kell fejezni a [Get()](../get/) hívással

## Lásd még

* Típusdefiníció [SharedPtr](../sharedptr/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)