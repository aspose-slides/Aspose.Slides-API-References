---
title: BuildObject()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Vytvoří objekt se sdíleným vlastnictvím.
type: docs
weight: 2250
url: /cs/system/buildobject/
---
## System::BuildObject(Args\&&...) funkce

Vytvoří objekt se sdíleným vlastnictvím.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ objektu k vytvoření |
| Args | Typy argumentů pro konstrukci objektu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| args | Args\&&... | Argumenty k předání konstruktoru objektu |

### Návratová hodnota

ObjectBuilder configured for shared pointer construction
## Poznámky

Vytvoří SharedPtr<T> a vrátí builder pro něj 
[Object](../object/) konstrukce musí být dokončena voláním [Get()](../get/)

## Viz také

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)