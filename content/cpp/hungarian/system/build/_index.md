---
title: Build()
second_title: Aspose.Slides for C++ API referencia
description: Objektum létrehozása közvetlen tulajdonjoggal.
type: docs
weight: 2289
url: /hu/system/build/
---
## System::Build(Args\&&...) függvény

Objektum létrehozása közvetlen tulajdonjoggal.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A létrehozandó objektum típusa |
| Args | Az objektum konstrukciójának argumentum típusai |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | Args\&&... | Az objektum konstruktorához továbbítani kívánt argumentumok |

### Visszatérési érték

Közvetlen objektumkonstrukcióra konfigurált ObjectBuilder

## Megjegyzések

[Object](../object/) konstrukciót be kell fejezni a [Get()](../get/) hívással

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)