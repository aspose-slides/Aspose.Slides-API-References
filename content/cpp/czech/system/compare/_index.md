---
title: Compare()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává dvě hodnoty.
type: docs
weight: 2731
url: /cs/system/compare/
---
## System::Compare(const TA\&, const TB\&) funkce

Porovnává dvě hodnoty.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TA | Typ prvního srovnávaného |
| TB | Typ druhého srovnávaného |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | const TA\& | První srovnávaný |
| b | const TB\& | Druhý srovnávaný |

### Návratová hodnota

- 1 pokud **a** je menší než **b**; 0 pokud jsou hodnoty stejné; 1 pokud **a** je větší než **b**

## System::Compare(const TA\&, const TB\&) funkce

Porovnává dvě hodnoty s plovoucí desetinnou čárkou.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TA | Typ prvního srovnávaného |
| TB | Typ druhého srovnávaného |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | const TA\& | První srovnávaný |
| b | const TB\& | Druhý srovnávaný |

### Návratová hodnota

- 1 pokud **a** je menší než **b**; 0 pokud jsou hodnoty stejné; 1 pokud **a** je větší než **b**

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)