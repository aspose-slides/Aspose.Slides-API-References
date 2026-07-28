---
title: InitObject()
second_title: Aspose.Slides C++ API referenciája
description: Elindítja egy objektum megosztott tulajdonjoggal történő inicializálását.
type: docs
weight: 2263
url: /hu/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) függvény

Elindítja egy objektum megosztott tulajdonjoggal történő inicializálását.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az inicializálandó objektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) az inicializáláshoz |

### Visszatérési érték

ObjectBuilder, megosztott pointer építéséhez konfigurálva

## Megjegyzések

[Object](../object/) inicializációt be kell fejezni a [Get()](../get/) hívással

## Lásd még

* Typedef [SharedPtr](../sharedptr/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)