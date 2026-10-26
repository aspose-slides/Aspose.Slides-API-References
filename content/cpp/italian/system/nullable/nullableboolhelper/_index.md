---
title: NullableBoolHelper()
second_title: Riferimento API Aspose.Slides per C++
description: Funzione di supporto per verificare se this e other sono entrambi non null e chiamare una lambda in tal caso. Utilizzata nelle implementazioni.
type: docs
weight: 105
url: /it/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const metodo

Funzione di supporto per verificare se this e **other** sono entrambi non null e chiamare una lambda in tal caso. Utilizzata nelle implementazioni.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Altro tipo nullable. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const T1\& | Altro valore nullable da confrontare. |
| f | const std::function\<**bool**()>\& | Lambda da chiamare se sia **this** sia **other** non sono null. |
| default_if_both_are_null | **bool** | Valore di ritorno se entrambi i valori sono null. |

### Valore restituito

false se **this** o **other** è null; **default_if_both_are_null** se entrambi sono null; risultato della chiamata **f** se entrambi non sono null.

## Vedi anche

* Classe [Nullable](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)