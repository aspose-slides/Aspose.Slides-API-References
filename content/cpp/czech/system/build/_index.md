---
title: Build()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvořte objekt s přímým vlastnictvím.
type: docs
weight: 2289
url: /cs/system/build/
---
## System::Build(Args&&...) funkce


Vytvořte objekt s přímým vlastnictvím.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Type of object to build |
| Args | Argument types for object construction |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| args | Args&&... | Arguments to forward to object constructor |

### Návratová hodnota

ObjectBuilder nakonfigurovaný pro přímou konstrukci objektu
## Poznámky



[Object](../object/) konstrukce musí být dokončena voláním [Get()](../get/) 

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)