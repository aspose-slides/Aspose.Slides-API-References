---
title: operator|=()
second_title: Riferimento API di Aspose.Slides per C++
description: Applica operator|=() al valore rappresentato dall'oggetto corrente usando il valore specificato come argomento a destra.
type: docs
weight: 261
url: /it/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) metodo


Applica [operator|=()](./) al valore rappresentato dall'oggetto corrente usando il valore specificato come argomento di destra.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il parametro del modello per far funzionare SFINAE. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | **bool** | Un valore booleano che viene usato come valore di destra del [operator|=()](./) applicato al valore rappresentato dall'oggetto corrente. |

### Valore di ritorno

Un riferimento all'oggetto stesso.

## Vedi anche

* Classe [Nullable](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)