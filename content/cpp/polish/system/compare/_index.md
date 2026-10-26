---
title: Compare()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Porównuje dwie wartości.
type: docs
weight: 2731
url: /pl/system/compare/
---
## System::Compare(const TA\&, const TB\&) funkcja

Porównuje dwie wartości.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TA | The type of the first comparand |
| TB | The type of the second comparand |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | const TA\& | The first comparand |
| b | const TB\& | The second comparand |

### Wartość zwracana

- 1 jeśli **a** jest mniejsze niż **b**; 0 jeśli wartości są równe; 1 jeśli **a** jest większe niż **b**

## System::Compare(const TA\&, const TB\&) funkcja

Porównuje dwie wartości zmiennoprzecinkowe.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TA | The type of the first comparand |
| TB | The type of the second comparand |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | const TA\& | The first comparand |
| b | const TB\& | The second comparand |

### Wartość zwracana

- 1 jeśli **a** jest mniejsze niż **b**; 0 jeśli wartości są równe; 1 jeśli **a** jest większe niż **b**

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)