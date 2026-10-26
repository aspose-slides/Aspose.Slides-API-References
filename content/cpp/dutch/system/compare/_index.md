---
title: Compare()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt twee waarden.
type: docs
weight: 2731
url: /nl/system/compare/
---
## System::Compare(const TA\&, const TB\&) functie

Vergelijkt twee waarden.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TA | Het type van de eerste vergelijkingsoperand |
| TB | Het type van de tweede vergelijkingsoperand |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | const TA\& | De eerste vergelijkingsoperand |
| b | const TB\& | De tweede vergelijkingsoperand |

### Retourwaarde

- 1 als **a** kleiner is dan **b**; 0 als de waarden gelijk zijn; 1 als **a** groter is dan **b**

## System::Compare(const TA\&, const TB\&) functie

Vergelijkt twee zwevendekommagetallen.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TA | Het type van de eerste vergelijkingsoperand |
| TB | Het type van de tweede vergelijkingsoperand |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | const TA\& | De eerste vergelijkingsoperand |
| b | const TB\& | De tweede vergelijkingsoperand |

### Retourwaarde

- 1 als **a** kleiner is dan **b**; 0 als de waarden gelijk zijn; 1 als **a** groter is dan **b**

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)