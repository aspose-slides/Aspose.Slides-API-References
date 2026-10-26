---
title: With()
second_title: Aspose.Slides C++ API Referencia
description: Klónozza a referencia rekordot, és alkalmazza rá az inicializáló függvényobjektumot.
type: docs
weight: 2614
url: /hu/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) függvény

Klónozza a referencia rekordot, és alkalmazza rá a inicializáló függvényobjektumot.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | Rekord típusa a klónozáshoz. |
| A | Inicializáló függvényobjektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Megosztott mutató az objektumra, amelyet klónozni és inicializálni kell. |
| initializer | const A\& | Inicializáló függvényobjektum, amelyet a rekord klónjára alkalmaznak. |

### Visszatérési érték

Megosztott mutató a klónozott rekordra.

## System::With(const T\&, const A\&) függvény

Másolja a struktúra rekordot, és alkalmazza rá a inicializáló függvényobjektumot.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | Rekord típusa a másoláshoz. |
| A | Inicializáló függvényobjektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| record | const T\& | Rekord, amelyet másolni és inicializálni kell. |
| initializer | const A\& | Inicializáló függvényobjektum, amelyet a rekord másolatára alkalmaznak. |

### Visszatérési érték

Másolt rekord.

## Lásd még

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)