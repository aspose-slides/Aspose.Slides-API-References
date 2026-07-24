---
title: Compare()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht zwei Werte.
type: docs
weight: 2731
url: /de/system/compare/
---
## System::Compare(const TA\&, const TB\&) Funktion

Vergleicht zwei Werte.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TA | Der Typ des ersten Vergleichswertes |
| TB | Der Typ des zweiten Vergleichswertes |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | const TA\& | Der erste Vergleichswert |
| b | const TB\& | Der zweite Vergleichswert |

### Rückgabewert

- 1 wenn **a** kleiner ist als **b**; 0 wenn die Werte gleich sind; 1 wenn **a** größer ist als **b**

## System::Compare(const TA\&, const TB\&) Funktion

Vergleicht zwei Gleitkommawerte.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TA | Der Typ des ersten Vergleichswertes |
| TB | Der Typ des zweiten Vergleichswertes |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | const TA\& | Der erste Vergleichswert |
| b | const TB\& | Der zweite Vergleichswert |

### Rückgabewert

- 1 wenn **a** kleiner ist als **b**; 0 wenn die Werte gleich sind; 1 wenn **a** größer ist als **b**

## Siehe auch

* Namespace [System](../)
* Library [Aspose.Slides](../../)