---
title: Compare()
second_title: Riferimento API Aspose.Slides per C++
description: Confronta due valori.
type: docs
weight: 2731
url: /it/system/compare/
---
## System::Compare(const TA\&, const TB\&) funzione

Confronta due valori.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TA | Il tipo del primo comparando |
| TB | Il tipo del secondo comparando |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | const TA\& | Il primo comparando |
| b | const TB\& | Il secondo comparando |

### Valore di ritorno

- 1 se **a** è minore di **b**; 0 se i valori sono uguali; 1 se **a** è maggiore di **b**

## System::Compare(const TA\&, const TB\&) funzione

Confronta due valori a virgola mobile.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TA | Il tipo del primo comparando |
| TB | Il tipo del secondo comparando |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | const TA\& | Il primo comparando |
| b | const TB\& | Il secondo comparando |

### Valore di ritorno

- 1 se **a** è minore di **b**; 0 se i valori sono uguali; 1 se **a** è maggiore di **b**

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)