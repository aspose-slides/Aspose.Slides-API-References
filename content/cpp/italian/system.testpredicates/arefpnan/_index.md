---
title: AreFPNaN()
second_title: Riferimento API di Aspose.Slides per C++
description: Dettagli del namespace
type: docs
weight: 1
url: /it/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) funzione

namespace [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Primo tipo a virgola mobile. |
| T2 | Secondo tipo a virgola mobile. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | T1 | Primo valore a virgola mobile. |
| rhs | T2 | Secondo valore a virgola mobile. |

### Valore di ritorno

Vero se sia **lhs** sia **rhs** sono valori a virgola mobile, falso altrimenti.

## Osservazioni

Verifica che due valori a virgola mobile siano entrambi NaN. Gestisce la situazione quando NaN non segnalante è supportato.

## System::TestPredicates::AreFPNaN(T1, T2) funzione

Verifica che due valori a virgola mobile siano entrambi NaN. Gestisce la situazione quando NaN non segnalante non è supportato.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### Parametri modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Primo tipo a virgola mobile. |
| T2 | Secondo tipo a virgola mobile. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | T1 | Primo valore a virgola mobile. |
| rhs | T2 | Secondo valore a virgola mobile. |

### Valore di ritorno

Restituisce sempre false poiché il valore NaN non è supportato.

## Vedi anche

* Namespace [System::TestPredicates](../)
* Libreria [Aspose.Slides](../../)