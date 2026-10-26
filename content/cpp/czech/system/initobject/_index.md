---
title: InitObject()
second_title: Aspose.Slides pro C++ API Reference
description: Spouští inicializaci objektu se sdíleným vlastnictvím.
type: docs
weight: 2263
url: /cs/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) funkce


Spouští inicializaci objektu se sdíleným vlastnictvím.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ objektu k inicializaci |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) k inicializaci |

### Návratová hodnota

ObjectBuilder nakonfigurovaný pro konstrukci sdíleného ukazatele

## Poznámky



[Object](../object/) inicializace musí být ukončena voláním [Get()](../get/) 

## Viz také

* Typedef [SharedPtr](../sharedptr/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)