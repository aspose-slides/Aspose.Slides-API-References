---
title: Compare()
second_title: Aspose.Slides for C++ API Referenciája
description: Két értéket hasonlít össze.
type: docs
weight: 2731
url: /hu/system/compare/
---
## System::Compare(const TA\&, const TB\&) függvény


Két értéket hasonlít össze.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TA | Az első összehasonlítandó típusa |
| TB | A második összehasonlítandó típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | const TA\& | Az első összehasonlítandó |
| b | const TB\& | A második összehasonlítandó |

### Visszatérési érték

- 1 ha **a** kisebb, mint **b**; 0 ha az értékek egyenlők; 1 ha **a** nagyobb, mint **b**


## System::Compare(const TA\&, const TB\&) függvény


Két lebegőpontos értéket hasonlít össze.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TA | Az első összehasonlítandó típusa |
| TB | A második összehasonlítandó típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | const TA\& | Az első összehasonlítandó |
| b | const TB\& | A második összehasonlítandó |

### Visszatérési érték

- 1 ha **a** kisebb, mint **b**; 0 ha az értékek egyenlők; 1 ha **a** nagyobb, mint **b**


## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)